=== tokpw Short URLs ===
Contributors: netandreus
Donate link: http://tokarchuk.ru/2013/03/tok-pw/
Tags: short url, short, url, shortener, url shortener, url shortening, urls, links, tinyurl, twitter, microblogging, tokpw
Requires at least: 3.0
Tested up to: 3.6
Stable tag: trunk
License: GPLv3

Automatically shortens the blog post URL via tok.pw.

== Description ==

This plugin adds ability to create short URL from the blog post permalink and stores it
in the database. The plugin currently use tok.pw as the only service and stores the data in the database of tok.pw.

Plugin homepage:
http://tokarchuk.ru/2013/03/tok-pw/

For support use WordPress.org or this page:
http://tokarchuk.ru/2013/03/tok-pw/

Thanks!

== Installation ==

1. Upload the `tokpw-short-urls` folder to `/wp-content/plugins/`.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. In the blog post edit window using Button "Get shortlink" to get short link of this post.

== Changelog ==

= 0.2 =
* Fix bug in call to undefined function.

= 0.1 =

* Starting developing plugin, based on k0nsl Short URLs (http://wordpress.org/extend/plugins/k0nsl-short-urls/)

== Frequently Asked Questions ==

= How do I use the tokpw_show_url() function? =
This function can be used in your theme files. For example, we echo tokpw_show_url() in post.php and this will show "http://tokpw.net/453".

== Upgrade Notice ==
= None. =
