=== Better Starter Widget ===
Contributors: khromov
Tags: widget
Requires at least: 3.3
Tested up to: 3.8
Stable tag: 1.0
License: GPL2

Effortlessly create  widgets with this template!

== Description ==
This widget is a template for creating your own Widget plugins.

**Usage**

After you have installed the plugin, you can start customizing it.
The only changes you need to do are:

* Rename the widget class from Widget_Better_Starter_Widget to something else (Example: Widget_My_Widget)
* Change the add_action call on the first line to match your new widget class name (right after ...return register_widget(" )
* Add your own fields in the _construct function by using the $this->add_field() method (There are some examples already)
* Write your custom code in the widget_output() function. There is an example of printing some variables already

Now, you have a few steps left before your widget is finished and you can publish it in the plugin directory or start using it on your projects:

* Rename the plugin folder to whatever you wish
* Rename the plugin PHP file to the same name as the plugin folder (if your folder is called my-widget, the PHP file should be my-widget.php
* Update the readme (That's this file!)
* Optional: If you want translations, find out your plugin textdomain by printing $this->textdomain, and create your .po and .mo files in the languages/ folder (Their name should be TEXTDOMAIN-locale, Example: widget_my_widget-sv_SE.po)
* Optional: Add other field types in the form() function. All you need to do is write the HTML for the field type. (Text fields are included.)

== Requirements ==
* Nothing

== Translations ==
* Swedish test translation provided

== Installation ==
1. Upload the `better-starter-widget` folder to `/wp-content/plugins/`
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Start developing!

== Frequently Asked Questions ==

None

== Changelog ==

= 1.0 =
Initial release
