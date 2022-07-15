# ublockOrigin_wordpressWhitelist
static filters to tame wordpress plugins

https://raw.githubusercontent.com/jawz101/ublockOrigin_wordpressWhitelist/master/my-ublock-static-filters_wordpressWhitelist.txt

According to [some stats, Wordpress is used on approximately 35% of websites on the Internet](https://kinsta.com/wordpress-market-share/).  I noticed a lot of 3rd party code is allowed as it is installed 1st party as a plugin.  Many of these served basic site functionality while many others were just revenue plugins and social sharing bloat.  Rather than pick what to block, this filter blocks all scripts from the /wp-content/plugins/ folder and whitelists those that fix basic site breakage.

[65 WordPress Plugins That Slow Down Your Website (And How To Use GTmetrix To Find Your Slowest Loading Plugins)](https://onlinemediamasters.com/slow-wordpress-plugins/)

[Plugins and Fast WordPress Sites – It’s not the Number of Plugins, It’s the Quality](https://wpengine.com/blog/plugins-and-fast-wordpress-sites-its-not-the-number-of-plugins-its-the-quality/)

[These plugins slow down your WordPress](https://servebolt.com/articles/these-plugins-slow-down-your-wordpress/)

[Use This Test to Find Out Which Plugins are Slowing Down Your WordPress Site](https://premium.wpmudev.org/blog/use-this-test-to-find-out-which-plugins-are-slowing-down-your-wordpress-site/)

-----------------------
Steps to fix breakages:

https://github.com/jawz101/ublockOrigin_wordpressWhitelist/wiki


A source list of many of the WP plugins out there:

http://plugins.svn.wordpress.org/

Essentially this blocks 96,000+ plugins and only allow 120 or so that sites use to make menus, add map widgets, etc.  Wordpress plugins are also a target for a lot of vulnerabilites so you're just eliminating the problem by blocking all of them and only letting the minimum amount through.
