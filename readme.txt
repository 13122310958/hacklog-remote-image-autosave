=== Hacklog Remote Image Autosave ===
Contributors: ihacklog
Donate link: http://ihacklog.com/donate
Tags: images, auto,autosave,remote
Requires at least: 3.2.1
Tested up to: 3.2.1
Stable tag: 1.0.1

== Description ==

This plugin can save remote images in the posts to local server automatically and add it as an attachment to the post.
自动保存日志中的远程图片到本地服务器并将保存后的文件作为日志的附件。

 
== Installation ==

1. Upload the whole `hacklog-remote-image-autosave` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to `Settings`==>`Hacklog RIA` to setup the options.

== Frequently Asked Questions ==

== Screenshots ==



== Changelog ==

= 1.0.0 =
* released the first version.

= 1.0.1 =
* improved the capability with Hacklog Remote Attachment plugin and Watermark Reloaded plugin.

== Arbitrary section ==

	if remote server is　 unreachable OR remote server Set against hotlinking，then the image url will remain as what it is in the post.
 	also ,this plugin will not handel with the situation when the remote server returns 302 http status.
