# ublockOrigin_wordpressWhitelist
static filters to tame wordpress plugins

According to WordPress, they are used on most webpages on the Internet.  I noticed a lot of 1st party content getting through your typical uBlock Origin filter lists that pertained to Wordpress Plugins.  Many of these served basic site functionality while many others were just revenue plugins and social sharing bloat.  Rather than pick what to block I made a filter to block all scripts from the /wp-content/plugins/ folder and whitelist those I encounter that fix basic site breakage.

My test:
copy the contents of this file into your MyFilters section (or import it).  Now, open the uBlock log screen and navigate to androidpolice.com (or any site heavy with wordpress plugins.
You will see very few allowed but several analytic plugin scripts blocked.  I don't know whether or not there is a performance penalty for these sorts of rules but it's just me seeing how much I will need to touch it.  Over the course of a couple of years I have had to add 24 exceptions so far but a cursory google search tells me there are thousands of plugins it is blocking.
