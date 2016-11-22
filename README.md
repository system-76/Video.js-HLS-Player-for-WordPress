# Video.js-HLS-Player-for-WordPress
[Video.js HLS Player] is a user-friendly plugin that supports HLS video playback on desktop and mobile devices. It's super easy to embed externally hosted .m3u8 HLS video packages using Video.js library on WordPress.

=== Video.js HLS Player ===
Contributors: Bruce Galpin
Donate link: https://www.socialite-media.com/
Tags: video, wpvideo, hls, flash, html5, iPad, iphone, ipod, mobile, playlists, embed video, videojs, flash player, player, video player, embed, lightweight, minimal, myvideo, responsive  
Requires at least: 4.2
Tested up to: 4.6
Stable tag: 1.0
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Embed video file beautifully in WordPress using Video.js HLS Player. Embed HTML5 compatible responsive video in your post/page with Video.js.

== Description ==

[Video.js HLS Player](https://www.socialite-media.com/videojs-hls-player-for-wordpress) is a user-friendly plugin that supports HLS video playback on desktop and mobile devices. It's super easy to embed externally hosted .m3u8 HLS video packages using Video.js library.

= Video.js HLS Player Features =

* Embed HLS video package into a post/page or anywhere on your WordPress site
* Embed MP4 video files into a post/page or anywhere on your WordPress site
* Embed responsive videos for a better user experience while viewing from a mobile device
* Embed HTML5 videos which are compatible with all major browsers
* Embed videos with poster images
* Embed videos using videojs player
* Automatically play a video when the page is rendered
* Embed videos uploaded to your WordPress media library using direct links in the shortcode
* No setup required, simply install and start embedding videos
* Lightweight and compatible with the latest version of WordPress
* Clean and sleek player with no watermark
* fallbacks for other HTML5-supported filetypes (WebM, Ogv)

= Video.js HLS Player Plugin Usage =

In order to embed a video create a new post/page and use the following shortcode:

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8"]`

Here, "url" is the location of the HLS video package file.

= Video Shortcode Options =

The following options are supported in the shortcode.

**MP4**

You can specify an MP4 video file in addition to the source HLS video file. This parameter is optional.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" mp4="http://example.com/wp-content/uploads/videos/myvid.mp4"]`

**WebM**

You can specify a WebM video file in addition to the source HLS video file. This parameter is optional.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" webm="http://example.com/wp-content/uploads/videos/myvid.webm"]`

**Ogv**

You can specify a Ogv video file in addition to the source HLS video file. This parameter is optional.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" ogv="http://example.com/wp-content/uploads/videos/myvid.ogv"]`

**Width**

Defines the width of the video file (Height is automatically calculated). This option is not required unless you want to limit the maximum width of the video.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" width="480"]`

**Preload**

Specifies if and how the video should be loaded when the page loads. Defaults to "auto" (the video should be loaded entirely when the page loads). Other options:

* "metadata" - only metadata should be loaded when the page loads
* "none" - the video should not be loaded when the page loads

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" preload="metadata"]`

**Controls**

Specifies if video controls should be displayed. Defaults to "true". In order to hide controls set this parameter to "false".

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" controls="false"]`

When you disable controls users will not be able to interact with your videos. So It is recommended that you enable autoplay for a video with no controls.

**Autoplay**

Causes the video file to automatically play when the page loads.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" autoplay="true"]`

**Poster**

Defines image to show as placeholder before the video plays.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" poster="http://example.com/wp-content/uploads/poster.jpg"]`

**Loop**

Causes the video file to loop to beginning when finished and automatically continue playing.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" loop="true"]`

**Muted**

Specifies that the audio output of the video should be muted.

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" muted="true"]`

**iOS Inline**

Force the video to play inline on iOS 10+

`[videojs_hls url="https://player.vimeo.com/external/xxxxxxxxx.m3u8" inline="true"]`

For detailed documentation please visit the [Video.js HLS Player](https://www.socialite-media.com/videojs-hls-player-for-wordpress) plugin page

== Installation ==

1. Go to the Add New plugins screen in your WordPress Dashboard
1. Click the upload tab
1. Browse for the plugin file (videojs-hls-player.zip) on your computer
1. Click "Install Now" and then hit the activate button

== Frequently Asked Questions ==

= Can this plugin be used to embed videos in WordPress? =

Yes.

= Are the videos embedded by this plugin playable on iOS devices? =

Yes.

= Can I embed responsive videos using this plugin? =

Yes.

== Screenshots ==

For screenshots please visit the [Videojs HLS Player](https://www.socialite-media.com/videojs-hls-player-for-wordpress) plugin page

== Upgrade Notice ==
none

== Changelog ==

= 1.0 =

* First commit
