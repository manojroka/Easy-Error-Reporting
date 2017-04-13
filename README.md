This simple plugin sets the error reporting level according to the user role. The script warnings and errors are hidden from subscribers and visitors while admin user can view and work on production environment.
This plugin helps to debug in production environment. On installation, the Subscribers and Visitors will not see the PHP errors, warnings or notices but Administrators, Editors, Authors and Contributors will be able to view and debug.
The error reporting level can be set from WP Dashboard >> EER Settings section for each user type. There will be no need to go to config file each time to enable/disable debug mode.

== Installation ==

Download the file and put it in your plugins directory.

Activate it.

Method 2 (WordPress Add New Plugin):

    Upload from Admin Section and Activate.

== Frequently Asked Questions ==

= Warnings and Notices in admin screen and site?  =

This is actually the purpose of this plugin. It shows all PHP errors, warnings and notices. We can track which component of the wordpress system is giving issue, like, any third party 
Plugin or template. A correct plugin or template should not throw such warnings or notices. To disable these warnings, Go to Dashboard >> EER Settings and select "NONE" for each role and Save Config.


