# protect-wordpress
Protect wordpress with .htacess


Protect wordpress with htaccess:)

require_once(ABSPATH.'wp-settings.php');
ini_set('display_errors','Off');
ini_set('error_reporting',E_ALL);
define('DISALLOW_FILE_EDIT',true);
define('DISALLOW_FILE_MODS',true);
ob_start();
?>

Set to: 404 in wp.config.php Also gets some speed!


* Protect: wp.contents folder, plugins,themes and uploads.
* Protect: wp-admin folder.

Core .htaccess for protection and speed.  Set: 444 files rights
- Updated: 22-06-25
- Updated 22-07-02 

Core .htaccess1 for speed and protection  Set: 444 files rights
in core. 
- Updated: 220-06-25
