=== MailPoet WP e-Commerce Add-on ===
Contributors: wysija, sebd86
Tags: mailpoet, wysija, wp-ecommerce, sebs studio, extension, add-on
Requires at least: 3.5.1
Tested up to: 3.8.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds a checkbox on checkout page for your customers to subscribe to your MailPoet newsletters.

== Description ==

> This plugin requires <a href="http://wordpress.org/plugins/wysija-newsletters/" rel="nofollow">MailPoet plugin</a> and <a href="http://wordpress.org/plugins/wp-e-commerce/" rel="nofollow">WP e-Commerce plugin</a>.

This simple plugin adds a checkbox on checkout page for your customers to subscribe to your MailPoet newsletters.

= Localization =
* English (US)[Default] - always included. mailpoet_wp_ecommerce_add_on.pot file in language folder for translations.

If you would like to do a translation for the plugin, you can do so via Transifex.  (https://www.transifex.com/projects/p/mailpoet-wp-e-commerce-add-on/)

Simply select or add a language you want to translate in and I will attach the language in the next version release. You will need an account on Transifex to do this.

If you have done a translation via PoEdit, then you are welcome to send that also. To send your translation files contact me. (http://www.sebs-studio.com/contact/?contacting=Translations)

I'll acknowledge your contribution here with either your full name or username given.

= Documentation =

For all documentation on this plugin go to: http://docs.sebs-studio.com/user-guide/extension/mailpoet-wp-ecommerce-add-on/

= Contributing =

To contribute to the plugin, visit https://github.com/seb86/MailPoet-WP-e-Commerce-Add-on/blob/master/CONTRIBUTING.md for details.

== Installation ==

= Minimum Requirements =

* MailPoet
* WP e-Commerce

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't even need to leave your web browser. To do an automatic install of MailPoet WP e-Commerce Add-On, log in to your WordPress admin panel, navigate to the Plugins menu and click Add New.

In the search field type "MailPoet WP e-Commerce Add-On" and click Search Plugins. Once you've found my plugin extension you can view details about it such as the the point release, rating and description. Most importantly of course, you can install it by simply clicking Install Now. After clicking that link you will be asked if you're sure you want to install the plugin. Click yes and WordPress will automatically complete the installation.

= Manual installation =

The manual installation method involves downloading my plugin and uploading it to your webserver via your favourite FTP application.

1. Download the plugin file to your computer and unzip it
2. Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installation's wp-content/plugins/ directory.
3. Activate the plugin from the Plugins menu within the WordPress admin.

= Setting up the Plugin =

Simply config this plugin under Products -> MailPoet by enabling the checkbox field to show on the checkout page.

You can also change the label of the checkbox. Default 'Yes, add me to your mailing list'

Next is 'Newsletters'. Each list you created in MailPoet that you have enabled to send to is listed here. Simply tick the checkbox next to the Newsletter list your customers will be subscribed to and press 'Save Changes'.

That's it, now when your customers tick the subscribe button on the checkout page, they will be subscribed to the newsletters you selected when processing an order.

= Upgrading =

Automatic updates should work like a charm; as always though, ensure you backup your site just in case.

== Screenshots ==

1. Subscribe checkbox field on checkout page.
2. WP e-Commerce MailPoet Settings.

== Changelog ==

= 1.0.2 - 24/03/2014 =

* ADDED - More languages, Arabic, Greek, Portuguese (Brazil), Russian
* ADDED - POT file
* CORRECTED - Default language from en_GB to en_US
* CORRECTED - if statment from last version change. Moved the function out of the plugin class for it to work again.
* REMOVED - Translation of the brand name 'MailPoet' only.

= 1.0.1 - 24/03/2014 =

* CORRECTED - If function 'mailpoet_lists' is already defined, then don't load again.

= 1.0.0 - 06/01/2014 =

 * Initial Release.
