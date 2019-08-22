=== Emergency Password Reset ===
Contributors: andymoyle
Donate link: http://www.themoyles.co.uk/
Tags: emergency password reset
Requires at least: 2.7.0
Tested up to: 5.0
Stable tag: 3.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin allows the admin to reset all the passwords and automatically email out the link to reset

== Description ==

This plugin allows the admin to reset all the passwords and automatically email out the link to reset

== Installation ==

1. Upload the `emergency-password-reset` directory to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Click on Emergency Password Reset in the Users menu
4. Click on the 'Reset Passwords' button

== Frequently Asked Questions ==
= How does it work? =
When you click rest passwords, the plugin recreates random passwords for every user and emails them the reset password link.

= Will I be secure now from a hack? =
Not necessarily. We advise you change your SALTS in the wp-config.php file which will force logouts for all users. Wordpress provide a <a href="https://api.wordpress.org/secret-key/1.1/salt/">tool</a> to generate new ones.
Check out our <a href="http://www.themoyles.co.uk/2013/02/so-your-wordpress-site-has-been-hacked/">blog post</a> on hacked Wordpress sites


== Screenshots ==
1. The main and only screen!

== Changelog ==
= 3.0 =
* Updated reset link
= 2.0 =
* Password reset link sent
* 1.0 Sends link to reset password page rather than new password
* 0.5 Form to change username from "admin"
* 0.4 Shows WP 4.0 compatability
* 0.3 Add Screenshot
* 0.2 Correct the title in readme.txt!
* 0.1 Initial release



== Upgrade notice ==
* 1.0

