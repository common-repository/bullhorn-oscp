=== Bullhorn Career Portal WordPress Plugin ===
Tags: Bullhorn, Career Portal, OSCP
Requires at least: 4.6
Requires PHP: 5.6
Tested up to: 5.9.1
Stable tag: 3.4.2
License: MIT

A simple, lightweight Wordpress plugin that adds Career Portal to any page in your Wordpress install by adding a snippet into the content of any page.

------
== Description ==
A simple, lightweight Wordpress plugin that adds Career Portal to any page in your Wordpress install by adding a snippet into the content of any page.


== Installation ==

Simply download the latest release and extract it into your plugins directory or search for it via WordPress plugins.

== Implementation ==

Getting your Career Portal to show up in WordPress is easy. Simply add and customize the following script to any page:


~~~~
[oscp]
~~~~


*Then, use the new plugin configuration to set your Career Portal settings.*

## Required Parameters
* `Corp Token` - Your Bullhorn corporation token. We give you this when you're Bullhorn CRM has Career Portal enabled.
* `Swim Lane` - Your Bullhorn swimlane (also provided by Bullhorn).
* `Accepted Resume Types` - The resume types you want to support.
* `Locale` - Language of your Career Portal.
* `Default View` - The default layout of your Career Portal.
* `Gender Race & Ethnicity Field` - Shows or hides the gender/race/ethnicity field for EEOC purposes
* `Veteran Status Field` - Shows or hides the veteran field for EEOC purposes
* `Disability Field` - Shows or hides the disability field for EEOC purposes

*Don't have these?* Reach out to Bullhorn's support staff. They can get these
to you in a heartbeat.

## Optional Parameters

* `Company Name` - The name you want to appear in the header of your Career Portal.
* `Height` - iFrame height attribute.
* `Width` - iFrame width attribute.
* `Scrollable` - iFrame scrollable attribute.
* `Linked In Client ID` - Your LinkedIn Client ID (to enable apply with LinkedIn)


== Contributing ==

Please feel free to fork this and hack on it. It's a free contribution to the Bullhorn and Wordpress communities. If you have suggestions or requests, please create a Github issue.