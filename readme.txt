=== Genesis Social Profiles Menu ===
Contributors: daveshine
Donate link: http://genesisthemes.de/en/donate/
Tags: genesis, genesiswp, genesis framework, social media, social networking, social profiles, social, icons, twitter, facebook, google plus, deckerweb
Requires at least: 3.0
Tested up to: 3.3-aortic-dissection
Stable tag: 1.0

This plugin adds a stylesheet for social profile icons for the WordPress custom menu - recommended for the use with Genesis Framework child themes.

== Description ==
This small and leightweight plugin is intended for the use with the popular Genesis Framework. It adds a special stylesheet for social profile icons for the WordPress custom menu system. The menu system is connected with the (Genesis) menu locations and also with widget areas because WordPress comes with a built-in custom menu widget. This way you can assign social profiles to a lot of locations on your site and easily add your own links, change sorting, change size, tooltips and opening in a new window/tab. So you have a lot of advantages over lots of other social profiles widget plugins around... As soon as you're figured out to add the CSS classes it's really easy, fast and flexible :-). For most use cases and regular Genesis Child Themes this should work really fine.

Please note: The plugin requires the Genesis Theme Framework

= Icon Sizes & Networks/Services =
* Sizes included: 16px / 24px / 32px
* Networks/Services included: Email / RSS/ATOM Feed / Facebook / Twitter / Google Plus / Flickr / YouTube / LinkedIn / Xing / GitHub

= Possible Locations / Areas for the Icons =
* Main Navigation - Primary Nav
* Subnavigation - Secondary Nav
* Header Right
* Sidebar (Primary)
* Sidebar Alt (Secondary)
* Footer Widgets

= Localization =
* English (default) - always included
* German - always included
* Your translation? - [Just send it in](http://genesisthemes.de/en/contact/)

= Icons License =
Licenced under an Attribution-Share Alike 2.0 UK: England & Wales Licence. We claim no right of ownership to the company logos used in these icons. Provision of these icons does not reflect endorsement of individual services. // To view a copy of this license, visit: http://creativecommons.org/licenses/by-sa/2.0/uk/
Icon set by Paul Robert Lloyd, http://paulrobertlloyd.com/2009/06/social_media_icons/

**[A plugin from deckerweb.de and GenesisThemes](http://genesisthemes.de/en/)**

* [*GenesisFinder* - Find then create. Your Genesis Framework Search Engine.](http://genesisfinder.com/)
* Please support me by [following on Twitter](http://twitter.com/#!/deckerweb) and [my Facebook page](http://www.facebook.com/deckerweb.service) - Thank you! ;-)
* [Also see my other plugins](http://genesisthemes.de/en/wp-plugins/) or see [my WordPress.org profile page](http://profiles.wordpress.org/users/daveshine/)

== Installation ==
1. Upload `genesis-social-profiles-menu` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Set up a custom menu in WordPress: Appearance > Menu -- or: edit/enhance an existing menu -- just add custom links to your desired services
4. Add the proper CSS classes to these custom links
5. Save menu to the desired menu location or use the WordPress widget for custom menu to place your profiles in any menu location or widget area

= Scheme for the CSS Classes =
It always goes like this: (service)-(iconset)-(size)

Example: twitter-prl-s16
-> you could also add the suffix "-s24" for 24px size or "-s32" for 32px size
-> change twitter to one of the 10 included services
-> "prl" stands for the used icon set - at the moment, there's only this one, maybe more sets following in the future...

= Available CSS classes =
* Email: email-prl-s16 / email-prl-s24 / email-prl-s32
* Feed: feed-prl-s16 / feed-prl-s24 / feed-prl-s32
* Twitter: twitter-prl-s16 / twitter-prl-s24 / twitter-prl-s32
* Facebook: facebook-prl-s16 / facebook-prl-s24 / facebook-prl-s32
* Flickr: flickr-prl-s16 / flickr-prl-s24 / flickr-prl-s32
* Google Plus: google-prl-s16 / google-prl-s24 / google-prl-s32
* LinkedIn: linkedin-prl-s16 / linkedin-prl-s24 / linkedin-prl-s32
* Xing: xing-prl-s16 / xing-prl-s24 / xing-prl-s32
* YouTube: youtube-prl-s16 / youtube-prl-s24 / youtube-prl-s32
* GitHub: github-prl-s16 / github-prl-s24 / github-prl-s32

= Helper CSS Classes to Add Some More Space :) =
There are also two helper classes included: `space-left` and `space-right` -- when using social items as an addition in a regular menu you might want to add some more space to have a better looking menu. Just an example, your menu goes like this:
Home Blog About [Twitter Icon] [Facebook]
-> You might add the space class to the [Twitter Icon] like so: `twitter-prl-s24 space-left` -- please note: no dots no commas are used here, only the classes separated by one space!

== Frequently Asked Questions ==
= Could I use this plugin also with another theme/framework? =
Good question but unfortunately this is no possible and not recommended. I've built in a theme check function so it's only useable with the Genesis Framework and its child themes. The reason for that is simple because the icons stylesheet references a lot of unique Genesis CSS IDs and classes so it will be nearly unuseable with other themes. However, you might have a look at the included stylesheet and maybe got inspired for your own stylesheet for your custom theme or even doing your own plugin with this...

== Screenshots ==
1. Contextual help tab open - section added to bottom of existing help area
2. Creating a new menu in WordPress
3. Adding CSS class to social profile menu item
4. The custom menu added to Secondary Menu location in Genesis (shown here with [free Autobahn child theme](http://genesisthemes.de/en/genesis-child-themes/autobahn/))
5. The custom menu added to Header Widget Right are - as a custom menu widget (shown here with [free Autobahn child theme](http://genesisthemes.de/en/genesis-child-themes/autobahn/))

== Changelog ==
= 1.0 =
* Initial release

== Upgrade Notice ==
If you have a cache plugin running in WordPress, it's recommended to delete/ clear the cache just after upgrading the plugin.

= 1.0 =
Just released into the wild.

== Translations ==
* English - default, always included
* German: Deutsch - immer dabei! [Download auch via deckerweb.de](http://deckerweb.de/material/sprachdateien/genesis-plugins/#genesis-social-profiles-menu)

== Icon Sizes ==
* 16px
* 24px
* 32px

== Networks/Services ==
* Email (envelope icon)
* RSS/ATOM Feed (orange feed icon)
* Social: Facebook / Twitter / Google Plus / Flickr / YouTube
* Business networks: LinkedIn / Xing
* Developer/Coding: GitHub

== Possible Locations / Areas for the Icons ==
* Main Navigation - Primary Nav
* Subnavigation - Secondary Nav
* Header Right
* Sidebar (Primary)
* Sidebar Alt (Secondary)
* Footer Widgets

== Idea Behind / Philosophy ==
Really, nothing spectacular. At the moment, this plugin is really useable but more of an experiment. I really like other plugins like the popular "Social Profiles Widget" but wanted something a bit more flexible and with another approach. I've released this as a plugin for other users to check it out so I could improve it. It's also intended for users who are no "ccs-coders at heart", so just activate and use :).
