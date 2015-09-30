# newspost
Demo newspost project in Codeigniter


1) File Location: [ProjectName]\newsportal_application_public\config\

i) File Name: config.php
$config['base_url'] = 'http://localhost/[ProjectName]/';
or
$config['base_url'] = 'http://sitedomain.com/';

ii) File Name: database.php
$db['default']['hostname'] = 'localhost';  //Change as your database hostname
$db['default']['username'] = 'root';  //Change as your database username
$db['default']['password'] = '';  //Change as your database password
$db['default']['database'] = 'newsportal';  //Change as your database name

====================================

2) Give the writeable permission to “upload” folder and its sub-folder’s.

=============================================

3) File Location: [ProjectName]\includes\

i) File Name: general_constant.php
define('PROJECT_NAME','[ProjectName]');   //[ProjectName] should be the folder name of the project
if (!defined('NO_REPLY_EMAIL')) define('NO_REPLY_EMAIL', 'noreply@newsportal.com'); //change noreply email as per your requirement
if (!defined('SUPPORT_EMAIL')) define('SUPPORT_EMAIL', 'support@newsportal.com'); // change support email as per your requirement
if (!defined('SITE_NAME')) define('SITE_NAME', 'News Portal');  //change site name as per your requirement
if (!defined('MAX_UPLOAD_IMAGE_SIZE')) define('MAX_UPLOAD_IMAGE_SIZE', 10000000);  //change max upload file size as per your requirement
