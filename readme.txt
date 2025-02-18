=== Redirect when Video Ends ===
Contributors: ethanluismcdonough
Donate link: 
Tags: HTML5 Video, Video, Redirect, JavaScript
Requires at least: 4.7
Tested up to: 4.8
Stable tag: 4.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A shortcode that allows you to embed an HTML5 video and redirect the page when the video is over

== Description ==

= Redirect when Video Ends =
This plugin will allow you to use the shortcode `[redirvid]` and embed an HTML5 video.  Once this video is over, the page will be automatically redirected

= Attributes for this shortcode =
`src` - The source of the video file.
`link` - The link that is opened when the video ends.
`target` - The default is `_self`, which redirects the page.  You can use any of the values that you could use with the [`target` attribute of an `<a>` tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attr-target).
`autoplay` - This  attribute specifies whether or not the video begins playing on its own.  The value `yes` means the video will autoplay.  The value `no` means that the video will not autoplay.  The default is value `no`.
`controls` - This  attribute specifies whether or not the video has user controls.  The value `no` means that the video will not have controls.  The value `yes` means 
`muted` - This  attribute specifies whether or not the video is muted.  The value `no` means that the video will not have controls.  The value `yes` means the video will have controls.  The default is value `no`.
`poster` - The source of the poster image of the HTML5 video.  This is the image that shows up before the video plays.
`class` - The HTML class of the video.
`id` - The HTML id of the video.


== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

== Frequently Asked Questions ==

= Does the redirect use JavaScript =

Yes, the redirect needs JavaScript.  If the JavaScript is turned off on the user’s device, this plugin won’t work.

== Screenshots ==

There are no screenshots
    

== Changelog ==

= 1.0 =
* The plugin has been created

= 1.1 = 
Allows muting, class, and id.

== Upgrade Notice ==
    
1.0 - first version
1.1 - current version
