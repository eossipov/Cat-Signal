=== Internet Defense League Cat Signal ===
Contributors: jazzs3quence
Donate link:https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AWM2TG
Tags: internet defense league, activism, cat signal, freedom, online activism
Requires at least: 2.7
Tested up to: 3.5.1
Stable tag: 1.0.6

A WordPress plugin to automatically load either the modal or the banner Cat Signal when there is an active campaign from the Internet Defense League.

== Description ==

** Update July 3, 2013 **
The Cat Signal is being raised on July 4th to support the 4th Amendment and oppose NSA internet surveillance. If you have this plugin installed, all you need to do is activate it and you will display your banner on your site. You can also [join the Thunderclap](https://www.thunderclap.it/projects/2594-july-4th-protest-nsa-spying) and spread the word on Facebook and Twitter. You can find out more information about this protest on [Restore the Fourth](http://www.restorethefourth.net/), [stopwatching.us](https://optin.stopwatching.us/) and [Fight for the Future](https://cms.fightforthefuture.org/july-4th-celebrate-4th-amendment-post-it-everywhere/).

The Internet Defense League is an online activist group organized to defend your online freedoms. When a bill is threatening to pass that would inhibit the way you live your online life, they put up the Cat Signal, a way to collectively black out or put notices on a large number of websites simultaneously.

This plugin adds the javascript for the Cat Signal to your site so you don't need to mess with the code. It's enqueued like any other javascript file and has an options page to select either the banner or the modal window option.

= About the plugin =

At first glance, it may appear that the plugin isn't doing anything because you don't have a banner or a modal window. *Don't panic!!!* What this means is that all is safe in Gotham and the Cat Signal has not been activated (read: there probably isn't an active IDL campaign running). To keep up to date on Internet Defense League campaigns, I recommend signing up for their mailing list (ed. note: I'm not affiliated with them at all, I'm just your friendly neighborhood internet activist). Once you're on the list, you'll get emails when they're about to launch a campaign.

**So how do I know if it's working?**
If you're savvy, you can check the HTML source of your site and check that either the `modal.js` or `banner.js` is loading. If it is, you're good to go, and the banner or modal window will work automagically when the IDL launch a new campaign.

If you're not as savvy, you can use the handy-dandy test link on the Cat Signal options page. This will display a banner or modal in the style of the actual alert while not actually displaying a pretty banner or graphic.

If you'd rather check manually, you can also add `?_idl_test=1` to the end of any page URL configured to display the alert and get the same test result.

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

== Screenshots ==

1. Modal option

2. Banner option

3. Options page

== Changelog ==

= 1.0.6 =
- fixed banner/modal bug (saved option was getting stripped in the validation function)
- moved IDL banner locally

= 1.0.5 =
- fixes validation _doing_it_wrong()

= 1.0.4 =
- Fixed open `<div>` tag
- added an option to define where the alert appears
- added link to test that the script is working

= 1.0.3 =
- Removed `die` function that was making the page quit if no option was set. Reported [here](http://wordpress.org/support/topic/not-working-on-my-site-3) and [here](http://wordpress.org/support/topic/indexphp-quits-after-wordpress-meta-tag).

= 1.0.2 =
- Changed how the validation pulled the options

= 1.0.1 =
- Added validation function

= 1.0 =
- Initial release.