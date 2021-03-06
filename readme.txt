=== Display Posts Shortcode ===
Contributors: billerickson
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MQKRBRFVRUV8C
Tags: shortcode, pages, posts, page, query, display, list
Requires at least: 3.0
Tested up to: 3.4.1
Stable tag: 1.8

Display a listing of posts using the [display-posts] shortcode

== Description ==

The *Display Posts Shortcode* was written to allow users to easily display listings of posts without knowing PHP or editing template files.

Add the shortcode in a post or page, and use the arguments to query based on tag, category, post type, and many other possibilities (see the Arguments). I've also added some extra options to display something more than just the title: include_date, include_excerpt, and image_size.

See the [WordPress Codex](http://codex.wordpress.org/Class_Reference/WP_Query) for information on using the arguments.

[Documentation](https://github.com/billerickson/display-posts-shortcode/wiki) | [Support Forum](https://github.com/billerickson/display-posts-shortcode/issues)

== Installation ==

1. Upload `display-posts-shortcode` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the *Plugins* menu in WordPress.
1. Add the shortcode to a post or page. 


== Changelog ==

**Version 1.8**

* Added `display_posts_shortcode_no_results` filter for displaying content if there's no posts matching current query.
* Add support for multiple post types. [display-posts post_type="page, post"]

**Version 1.7**

* Added `id` argument to specify specific post IDs
* Added `display_posts_shortcode_args` filter in case the arguments you want aren't already included in the shortcode. See example: http://www.billerickson.net/code/display-posts-shortcode-exclude-posts/

**Version 1.6**

* Added `post_parent` where you can specify a parent by ID, or you can say `post_parent=current` and it will use the current page's ID.
* Added `wrapper` where you can decide if the posts are an unordered list, ordered list, or div's
* Added support for multiple taxonomy terms (comma separated) and taxonomy operator (IN, NOT IN, or AND).

**Version 1.5**
* For the sake of clarity I'm changing version numbers. No feature changes

**Version 0.1.5**
* Added a filter (display_posts_shortcode_output) so you can modify the output of individual posts however you like.

**Version 0.1.4**

* Added post_type, taxonomy, tax_term, and include_excerpt
* Added classes to each part of the listing (image, title, date, excerpt) to make it easier to change the look using CSS

**Version 0.1.3**

* Updated Readme

**Version 0.1.2**

* Added image_size option

**Version 0.1.1**

* Fix spacing issue in plugin

**Version 0.1**

* This is version 0.1.  Everything's new!

