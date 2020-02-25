# ublockOrigin_wordpressWhitelist
static filters to tame wordpress plugins

According to [some stats, Wordpress is used on approximately 35% of websites on the Internet](https://kinsta.com/wordpress-market-share/).  I noticed a lot of 1st party content getting through your typical uBlock Origin filter lists that pertained to Wordpress Plugins.  Many of these served basic site functionality while many others were just revenue plugins and social sharing bloat.  Rather than pick what to block I made a filter to block all scripts from the /wp-content/plugins/ folder and whitelist those I encounter that fix basic site breakage.

My test:
copy the contents of this file into your MyFilters section (or import it).  Now, open the uBlock log screen and navigate to androidpolice.com (or any site heavy with wordpress plugins.
You will see very few allowed but several analytic plugin scripts blocked.  I don't know whether or not there is a performance penalty for these sorts of rules but it's just me seeing how much I will need to touch it.  Over the course of a couple of years I have had to add 24 exceptions so far but a cursory google search tells me there are thousands of plugins it is blocking.


I may be onto something

[65 WordPress Plugins That Slow Down Your Website (And How To Use GTmetrix To Find Your Slowest Loading Plugins)](https://onlinemediamasters.com/slow-wordpress-plugins/)

[Plugins and Fast WordPress Sites – It’s not the Number of Plugins, It’s the Quality](https://wpengine.com/blog/plugins-and-fast-wordpress-sites-its-not-the-number-of-plugins-its-the-quality/)

[These plugins slow down your WordPress](https://servebolt.com/articles/these-plugins-slow-down-your-wordpress/)

[Use This Test to Find Out Which Plugins are Slowing Down Your WordPress Site](https://premium.wpmudev.org/blog/use-this-test-to-find-out-which-plugins-are-slowing-down-your-wordpress-site/)
