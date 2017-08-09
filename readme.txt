=== Related Posts for WordPress ===
Contributors: microkid,
Tags: related, posts, seo, content, articles, relevant, similar, custom posts, custom post types
Requires at least: 2.5
Tested up to: 3.3.1
Stable tag: 4.0.3

Increase your pageviews and SEO by manually selecting related posts for your content. Easy reciprocal linking of related posts and pages.

== Description ==

This powerful plugin makes it super easy to manually select related posts for your content. You can search and select posts that fit **your** criteria, all from within the write/edit post screen.

Creating a system of related items on your website will result in more page views per unique visitor, and will improve Google's understanding of your content.

As mentioned by [WordPress SEO](http://yoast.com/articles/wordpress-seo/#relatedposts "WordPress SEO and Related Posts ") master Yoast:

> A very good alternative is Microkid's related post plugin, which lets you manually pick related posts. This might cost a bit more time before you hit publish but might very well be worth your while.

You can display related posts automatically underneath your content, use a shortcode or use the widget. Or, if you have some development skills, you can use one of the available API functions for full control of the way related posts are displayed on your website.

With its full support for Custom Post Types, this plugin will work perfectly for both basic and advanced WordPress installations.

See the official plugin homepage for [Related Posts for WordPress](http://www.microkid.net/wordpress/related-posts/ "Wordpress Related Posts") for more info and discussion.

= Features =

* Easily find posts or pages that might be related to the one you are writing with an integrated AJAX powered search utility
* Easily add and remove relations with a single click
* Extreme flexibility in the customization of the way the related posts are displayed on your website
* The relationship created works **reciprocal**, which means that if post A is added as related to post B, post B is automatically added as related to post A as well (this option can be turned off easily through the settings panel)
* Custom post types support
* Multiple widget support with extended customization options
* Shortcode support: add the [related-posts] shortcode to your post content to display related posts anywhere you want
* Automatically display a list of related posts underneath your posts content. No need to add any PHP tags in your template files, but several [functions](http://www.microkid.net/wordpress/related-posts/#API "Related Posts for WordPress API functions") available for advanced users.
* Available in a growing number of languages

== Installation ==

1. Download the plugin and unzip,
1. Put the microkids-related-posts folder in your wp-content/plugins folder,
1. Activate the plugin through the WordPress admin,
1. The plugin will automatically display related posts underneath your posts content. You can change this and some other settings through the plugins options page under Settings > Related Posts.
1. Check out the Related Posts options under the Settings menu to further customize!

**Note:** If you want to display the related posts somewhere else on your page, there is a set of [API functions](http://www.microkid.net/wordpress/related-posts/#API "Related Posts for WordPress API functions") you can place in your theme files. You can also use the [related-posts] shortcode to display related posts within your content, or use the available widget.

== Frequently Asked Questions == 

= Does this plugin have a widget? =
Yes, if your theme supports it you can display multiple related posts widgets in your dynamic sidebars.

= Does this plugin work with WordPress versions &lt; 2.5? =
No, it is not backward compatible with WordPress version older than 2.5.

= Can I add the related posts to my post text using a shortcode? =
Yes, you place [related-posts] anywhere in your text to display the related posts wherever you want. Additionally, you can add an attribute "posttype" to the shortcode to display the related posts of a specific post type only. Example: [related-posts posttype=page]

= What will be displayed if there are no related posts? =
You can use a custom message, or display nothing at all (no text, no code).

= I need more options. How can I fully customize the way the related posts are displayed? =
There is a set of [API functions](http://www.microkid.net/wordpress/related-posts/#API "Related Posts for WordPress API functions") available you can use in your themes to display the related posts in any way you can think of.

= I'm having trouble using this plugin. How can I reach you? =
Please leave me a comment at the [Related Posts for WordPress](http://www.microkid.net/wordpress/related-posts/ "Related Posts for WordPress") homepage.

== Screenshots ==

1. The plugin will appear in the write/edit post screen.
2. The Related Posts options page allows you to completely customize the way related posts are displayed
3. The Related Posts widget lets you automatically display related posts in your dynamic sidebar

== Change Log ==

= 4.0.3 =
* Fixed bug that would prevent related posts from showing when using automatic sorting and reciprocal linking turned off.

= 4.0.2 =
* Added hook for proper database configuration when upgrading

= 4.0.1 =
* Fixed an issue where proper DB columns for manual positions weren't generated
* Fixed issue where automatic ordering wasn't updating in settings

= 4.0 =
* Added support for thumbnails
* Added support for manually ordering related posts
* Fixed bug in widget that broke the theme's widget container and title HTML
* Added a better way of implementing the AJAX search in the Related Posts box on the edit screen. This should take care of the problems some people were having with the search not working.
* Added a default CSS file for styling the Related Posts on your site (this can be turned off through the settings)
* Improved the layout of the Related Posts box on the post edit page

= 3.0.1 =
* Fixed an HTML bug that would occur if there are no related posts and the "when there are no related posts display this text" option was selected

= 3.0 =
* Added support for WP 3.0 custom post types - Create relations with custom post types, display related posts in one list or seperate them by post type
* Added controlled order - You can now order the related posts by date, title or random
* Added internationalization - You can now display the plugin settings page in your own language. I have already added Dutch, please send your language files to microkid.net@gmail.com
* Fixed support for non Western Latin characters (Cyrillic, Arabic, etc.)
* Plus a zillion small bugfixes and enhancements!

= 2.5 =
* Improved the AJAX search utility with a more fluent way of updating the results list
* Added support for multiple instances of the widget by using the new [Widget API](http://codex.wordpress.org/Version_2.8#New_Widgets_API) introduced in WordPress 2.8
* Fixed a bug where the widget wouldn't show on pages
* Related private posts are now displayed to users who have the necessary priviliges

= 2.4 =
* You can now add drafts and planned posts as related posts, without them appearing on your site before they are properly published.
* Added shortcode support - you can now place the [related-posts] shortcode within the content of your post to display the related posts anywhere you want.
* (For advanced users) Added a parameter to the MRP_get_related_posts function to optionally get the related posts in an object, so you can easily use it in other plugins or your own custom way of displaying the list of related posts. For documentation on this, see [the API section](http://www.microkid.net/wordpress/related-posts/#API "Related Posts for WordPress API functions").

= 2.3 =
* Added option to manage search scope: post content, post title, or both
* Slightly improved the search query when searching for related posts
* Added a limit of 50 search results to help the plugin work smoothly on larger sites.
* Fixed some IE6 layout issues
* Fixed issue where, in non reciprocal mode, after editing a post it would lose its passive connections to other posts
* Fixed issue where hitting the enter key while in the search box would submit the page
* Fixed issue where hitting a none character key (like shift, ctrl, etc.) in the search box would trigger the AJAX search

= 2.2 =
* Added optimized SQL for related posts query provided by [Peter Raganitsch](http://blog.oracleapex.at "Peter Raganitsch]")
* Added option for turning reciprocal function off provided by [Brock Boland](http://www.brockboland.com/ "Brock Boland]")
* Fixed some layout issues in WordPress 2.7
* The search tool now searches in post title and post content.

= 2.1.1 =
* Solved an issue with shorthand PHP tags.

= 2.1 =
* Solved an issue where in WP 2.6 relationships with revisions were created when editing a post.

= 2.0 =
* Added the option to display related posts underneath your post content automatically
* Added the extended customization options for the way the list of related posts is displayed:
 * Using a custom title
 * Choosing the HTML header element (h1, h2, etc.) of the title for the related posts section
 * Custom message to display when there are no related posts, with the option no displaying anything at all (no text, no code)
* Added widget support
* Added support for adding related pages

= 1.1 =
* Fixed a small issue with the paths to the .js and .css files which made the plugin break on blogs that reside in subdirectories.

== Upgrade Notice ==

= 4.0 =
Sit tight for this major upgrade! Lots of new features and fixes, including thumbnail support and manual ordering of related posts!
