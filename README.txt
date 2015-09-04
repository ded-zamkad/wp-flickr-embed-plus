=== Wordpress Flickr Embed Plus	 ===

Plugin Name: Wordpress Flickr Embed Plus
Contributors: 
Author URI: http://ded_zamkad.livejournal.com
Plugin URI: https://github.com/ded-zamkad/wp-flickr-embed-plus
Tags: admin, images, posts, flickr, embed, exif
Requires at least: 3.4.1
Tested up to: 4.2.3
Stable tag: 1.0.0

== Description ==

Wordpress Flickr Embed Plus is a Wordpress plugin that provides an interactive interface for adding Flickr images to your posts. The interface is conveniently launched from the visual editor toolbar.

This is a fork of the (https://wordpress.org/plugins/wp-flickr-embed/) plugin for Wordpress and provides numerous bug fixes and enhancements over the original.

= New Features =
* Supports EXIF metadata as label for photo

= Features =
* Search for an select any public photo or a private one from your photostream (requires Flickr authorization).
* Sort search results by date taken or date posted
* Insert a photo anywhere in your post, choosing its title, size and how it should be aligned to the text.
* Link the photo back to its Flickr page or to a different-sized version of itself.
* Supports Lightbox and Lightview popups.


Source on Github: https://github.com/ded-zamkad/wp-flickr-embed-plus

*Note:* This plugin requires PHP 5.2.

== Installation ==

1. Download and unzip the zip file into your Wordpress `plugins` folder such that the plugin files are at: `wp-content/plugins/wp-flickr-embed-plus/...`
1. Activate the plugin within your blog's administration options.
1. Goto menu `Settings > Flickr Embed Plus`. Here you can authenticate with Flickr and edit other settings.
1. All done!

== Screenshots ==

1. The Wordpress Flickr Embed Plus options page under the `Settings` menu
1. The Wordpress Flickr Embed Plus panel that appears on the post insertion screen

== Frequently Asked Questions ==

= How do I authorize the plugin to access my private Flickr photos? =

1. Goto `Settings > WP Flickr Embed Plus` and click the `Authorize with Flickr` button.
2. This will take you to Flickr where upon you should login and follow the instructions.
3. Once you've authorized it you should be taken back to the options page with a success message.

= I don't have a Flickr account. Can I still use the plugin? =

Yes you can. You will still be able to insert any public photo available on Flickr. Authorization is only needed if you wish to access your own private photos on Flickr.

= How do I get it working with Lightbox? =

1. Goto `Settings > Flickr Embed Plus`
2. Set `Link the photo to` to `the photo itself`.
3. Set `The "rel" attribute of link tag` option to `lightbox`.
4. Click `Update options`.


== Changelog ==


= 1.0 (Sep 5, 2015) =
* First version
