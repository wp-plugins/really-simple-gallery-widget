=== Really Simple Gallery Widget ===
Contributors: helenyhou
Donate link: http://www.helenhousandi.com/wordpress/donate/
Tags: gallery, widget
Requires at least: 2.8
Tested up to: 3.1
Stable tag: trunk

Simple widget for displaying images attached to a specific post or page.

== Description ==

Really Simple Gallery Widget adds a widget to display images that are attached to a post or page, no extra uploading or creating custom post types required. Especially helpful if you create photo gallery pages using the built-in WordPress gallery and just want to be able to display those images in a widget area.

= Features =
* Add as many widgets as you want, wherever you want
* Select a number of images
* Select any registered size in WordPress
* Display the images in ascending, descending, or random order
* Show or hide captions
* Link the images to the original file, post, anchor in the post, attachment page, or nothing
* Add a prefix to the link and image title (appears as a tooltip)
* Use a rel attribute for the link - great for lightboxes

== Installation ==

Really Simple Gallery Widget is most easily installed automatically via the Plugins tab in your blog administration panel.

= Manual Installation =

1. Upload the `really-simple-gallery-widget` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Head over to Appearance &rarr; Widgets to set up one or more Really Simple Gallery Widgets

== Frequently Asked Questions ==

= How do I get the ID for the post or page? =

The easiest way is to mouseover or click an edit link for the post or page in question. The ID number will appear in the URL; e.g. `http://yoursite.com/wp-admin/post.php?post=41&action=edit` indicates that the ID of the post or page you want to reference is 41.

= Why is the anchor link not working? =
The anchor link relies on the ID that WordPress automatically generates when you insert an image with a caption. If you inserted the image manually or without a caption, the anchor won't jump you to the spot in the page. The ability to specify an anchor may be added at a later time, or you can just add the ID (attachment_##) to the img tag.

= I selected a registered size but the images are showing up huge or in the wrong size. =
The images may be missing the thumbnails of that size and by default will pull the full size image instead. Try using Viper007Bond's fantastic [Regenerate Thumbnails](http://wordpress.org/extend/plugins/regenerate-thumbnails/ "Regenerate Thumbnails") plugin to create new versions for any new or changed image sizes.

== Screenshots ==

1. Widget options
2. Sample display with prefixed title showing

== Changelog ==

= 1.0 =
* First version

== Upgrade Notice ==

= 1.0 =
Original release