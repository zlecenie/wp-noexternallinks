=== WP No External Links ===
Author: Jehy
Tags: seo, link, links, publisher, post, posts, comments
Requires at least: 2.6
Tested up to: 2.7.1
Stable tag: 2.0
Mask all external links - make them internal or hide. On your own posts, comments pages, authors page - no more PR\CY dropping!

== Description ==

Mask all external links to internal! In your own posts, comments pages, authors page... It does not change anything or write to base - just processes output.

Now you don't need to worry about your page rank or index, dropping because of spam bots. You write any kind of http link - and it becomes internal or hidden! You can configure plugin to work with your own posts, pages comments and authors's profiles. Of cause, the link will still be usable :).

####NEW!!!!!
Now you can also disable link rewriting, and use "rel=nofollow" and &lt;noindex&gt; tag instead of it - everything as you wish!   
Also in version 2.0 you can make all links open ine new window!   
Also, after many requests, I finally made an option to disable masking for concrete URLs and posts.  
Also, plugin works now without any magic with .htacess - you just install it and it works, and determines itself, if you need to rewrite permalinks, or use default link structure.  
Have fun!

####Example

In short, your links like "http://gmail.com" will be masked into  
"http://YourBlog.com/goto/http://gmail.com" - or  
"http://YourBlog.com?goto=http://gmail.com"

Also you can add <b>rel=nofollow</b> attribute, <b>&lt;noindex&gt;</b> tag, and <b>target="_blank"</b> to your links!

> Is it an evil hack and black SEO?!   
Before you tell such awful things, read at lest [Google's topics on SEO](http://www.google.com/support/webmasters/bin/topic.py?topic=8522)   



####History

0.01 - first release  
0.02 - multilanguagal release  
0.03 - bugfix  
0.04 - Activation \ Deactivation improved, optimization, localization settings now stored as options  
0.05 - bugfix for wrong html parsing  
0.06 - bugfix for email links  
0.07 - better work for sites wihout mod_rewrite  
0.071 - russian translation corrected  
2.0 - Many significant changes, including urls and post exclusion from masking, another rewrite structure, and new options.

####Localization

* English
* Russian


####Please!
If you don't rate my plugin as 5/5 - please write why - and I will add or change options and fix bugs. It's very unpleasant to see silient low rates.  
If you don't understand what this plugin does - also don't rate it. SEO specialists only.

== Installation ==

1. Upload the complete folder `wp-noexternallinks` to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress
2. [Optional] Configure plugin via admin options-&gt;Wp-NoExternalLinks link
4. Write posts with any kind of links, watch comments with links - and enjoy =^___^=

== Frequently Asked Questions ==
- How can I exclude my page with links from masking?   
Now you just put URLS you need to the exclusion list, or disable masking for concrete post - and everything's OK!!!