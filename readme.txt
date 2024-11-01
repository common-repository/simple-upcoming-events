=== Simple Upcoming Events ===
Contributors: hideaki
Tags: widget, Post, posts, plugin, sidebar, upcoming, events
Stable tag: trunk
Tested up to: 2.9.1

Displays a list of posts for upcoming events. 
Event dates are specifed as "date" Custom Field.
Depends on NO external services like Google Calendar.

== Installation ==
1. Upload `simple-upcoming-events.php` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Add 'Simple Upcoming Events' widget through 'Appearance' > 'Widgets' menu.

== Usage ==
When you publish a new post, add a Custom Field named "date", and set its value to the date the event will take place (i.e. "2010-05-02"). That's it!

Optionally, you can specify the name of the event with a Custom Field named "event-name". If you don't specify that, the title of the post is used as the name of the event.

== Changelog ==
= 1.0.1 = 
* Removed usage of date_create, which was added in PHP 5.2, to support PHP 4.

= 1.1.0 =
* Added "event-name" Custom Field.
* Better adjustment for themes.

= 1.1.1 =
* Being more forgiving of different date formats of date Custom Field like "2009.9.27" or "2009/09/27"
* Showing reference of date format in a new window.
