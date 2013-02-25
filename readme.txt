=== Updater ===
Contributors: bestwebsoft
Donate link: https://www.2checkout.com/checkout/purchase?sid=1430388&quantity=10&product_id=13
Tags: plugin, core, wordpress, update
Requires at least: 3.0
Tested up to: 3.5.1
Stable tag: 1.05
License: GPLv2 or later

This plugin allows you to update plugins and WP core.

== Description ==

This plugin updates plugins and WP core. You can also choose the auto mode or the manual mode for the updating and add email notification.

= User guide =

1. After downloading and activating the plugin 'Updater', you should go to the page 'Updater | options' in 'BWS Plugins' menu, where plugin settings are located.
2. On this page you should choose the type mode for the plugin and tune settings for the email notification.
3. If you want to update your plugins or WP core in the manual mode you should go to the page 'Updater | tools'. If WordPress or some of your plugins need to be updated it will be displayed in red. Check it and click 'update'.

= Translation =

* Russian (ru_RU)

If you create your own language pack or update an existing one, you can send <a href="http://codex.wordpress.org/Translating_WordPress" target="_blank">the text of PO and MO files</a> for <a href="http://bestwebsoft.com/" target="_blank">BWS</a> and we'll add it to the plugin. You can download the latest version of the program for work with PO and MO files  <a href="http://www.poedit.net/download.php" target="_blank">Poedit</a>.

= Technical support =

Dear users, our plugins are available for free download. If you have any questions or propositions regarding functionality of our plugins (current options, new options, current issues) please feel free to contact us. Please note that we accept requests in English language only. All messages on another languages wouldn't be accepted. 

Also, emails which are reporting about plugin's bugs are accepted for investigation and fixing. Your request must contain URL of the website, issues description and WordPress admin panel access. Plugin customization based on your Wordpress theme is a paid service (standard price is $10, but it could be higer and depends on the complexity of requested changes). We will analize existing issue and make necessary changes after 100% pre-payment.All these paid changes and modifications could be included to the next version of plugin and will be shared for all users like an integral part of the plugin. Free fixing services will be provided for user who send translation on their native language (this should be a new translation of a certain plugin, and you can check available translations on the official plugin page).

== Installation ==

1. Upload `updater` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Plugin settings are located in 'BWS Plugins', 'Updater', 'options'.

== Frequently Asked Questions ==

= The plugin doesn't send any emails =

Please follow instructions below:

1) Please check plugin's settings '/wp-admin/admin.php?page=updater-options'

2) The plugin sends email in case if you have updates. If you do not have updates it will not send the email.

3) It is possible that email messages are detected like spam on a server. Enter email ('Sender's name and email address' block), for example, gmail account or similar. If the message is approved (it will be sent), then the email filtering is configured on your server.

4) Have you got notifications about new users registration? If no, perhaps you didn't configure email sending. Then You need to install the extra plugin called WP-mail-SMTP and configure it.


= The plugin stopped sending emails after some time. What's the problem? =

The plugin sends email in case if you have updates. If you do not have updates it will not send the email.


= The time of sending does not match what I have specified (or default value). =

The function for sending emails and updating is triggered when the site is active (when someone comes to your site.) If there is no any activity, then it will run when the first activity appears. So the time can be shifted.


= How often the plugin will search for or/and update plugins and WordPress if I do not specify the time? =

By default, Updater performs this every 12 hours. In auto mode, the Updater updates plugins or WP core, if updates are available.


= I want the plugin to search for or/and update plugins and WordPress every 0.5 hours =

It's impossible. The number of hours must be integer and it must not include more 5 digits.

== Screenshots ==

1. Updater Options page.
2. Updater page in the BWS admin area.

== Changelog ==

= V1.05 - 25.02.2013 =
* Bugfix : The code refactoring was performed.
* Update : Changed location of the pages.

= V1.04 - 13.02.2013 =
* NEW : Add sending a test email.
* NEW : Add Frequently Asked Questions.

= V1.03 - 06.02.2013 =
* Bugfix : Bug in time to send mail wase fixed.
* Update : Email that send when new versions of plugins or WordPress are available was updated.

= V1.02 - 28.01.2013 =
* NEW : Add sending email when new versions of plugins or WordPress are available.
* Bugfix : Bugs in admin menu were fixed.
* Update : Css-style was updated.
* Update : We updated all functionality for wordpress 3.5.1.

= V1.01 - 17.01.2013 =
* Bugfix : The code refactoring was performed.
* NEW : Css-style was added.

== Upgrade Notice ==

= V1.05 =
The code refactoring was performed. Changed location of the pages.

= V1.04 =
Add sending a test email. Add Frequently Asked Questions.

= V1.03 =
Bug in time to send mail wase fixed. Email that send when new versions of plugins or WordPress are available was updated.

= V1.02 = 
Add sending email when new versions of plugins or WordPress are available. Bugs in admin menu were fixed. Css-style was updated. We updated all functionality for wordpress 3.5.1.

= V1.01 =
The code refactoring was performed. Css-style was added.
