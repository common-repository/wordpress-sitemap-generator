=== WordPress Sitemap Generator ===
Contributors: arnee
Donate link: http://www.escalateseo.com
Tags: seo, google, sitemaps, google sitemaps, yahoo, msn, ask, live, xml sitemap, xml
Requires at least: 2.1
Tested up to: 3.3
Stable tag: 1.2.0

This plugin will generate a special XML sitemap which will help search engines to better index your blog.

== Description ==

This plugin will generate a special XML sitemap which will help search engines like Google, Bing, Yahoo and Ask.com to better index your blog. With such a sitemap, it's much easier for the crawlers to see the complete structure of your site and retrieve it more efficiently. The plugin supports all kinds of WordPress generated pages as well as custom URLs. Additionally it notifies all major search engines every time you create a post about the new content.

== Installation ==

1. Upload the full directory into your wp-content/plugins directory
2. Use your favorite FTP program to create two files in your WordPress directory (that's where the wp-config.php is) named sitemap.xml and sitemap.xml.gz and make them writable via CHMOD 666. More information about CHMOD and how to make files writable is available at the [WordPress Codex](http://codex.wordpress.org/Changing_File_Permissions) and on [stadtaus.com](http://www.stadtaus.com/en/tutorials/chmod-ftp-file-permissions.php). Making your whole blog directory writable is NOT recommended anymore due to security reasons.
4. Activate the plugin at the plugin administration page
5. Open the plugin configuration page, which is located under Options -> XML-Sitemap and build the sitemap the first time. If you get a permission error, check the file permissions of the newly created files.
6. The plugin will automatically update your sitemap of you publish a post, so theres nothing more to do :)

== Frequently Asked Questions == 

= There are no comments yet (or I've disabled them) and all my postings have a priority of zero! =

Please disable automatic priority calculation and define a static priority for posts.

= Do I always have to click on "Rebuild Sitemap" if I modified a post? =

No, if you edit/publish/delete a post, your sitemap is automatically regenerated

= So much configuration options... Do I need to change them? =

No, only if you want to. Default values should be ok!

= Does this plugin work with all WordPress versions? =

This version works with WordPress 2.1 and better. If you're using an older version, please check the [Google Sitemaps Plugin Homepage](http://www.escalateseo.com/ "Google (XML) Sitemap Generator Plugin Homepage") for the legacy releases. There is a working release for every WordPress version since 1.5

= I get an fopen and / or permission denied error or my sitemap files could not be written =

If you get permission errors, make sure that the script has the right to overwrite the sitemap.xml and sitemap.xml.gz files. Try to create the sitemap.xml resp. sitemap.xml.gz at manually and upload them with a ftp program and set the rights with CHMOD to 666 (or 777 if 666 still doesn't work). Then restart sitemap generation on the administration page. A good tutorial for changing file permissions can be found on the [WordPress Codex](http://codex.wordpress.org/Changing_File_Permissions) and at [stadtaus.com](http://www.stadtaus.com/en/tutorials/chmod-ftp-file-permissions.php).