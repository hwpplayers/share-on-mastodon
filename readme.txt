=== Share on Mastodon ===
Contributors: janboddez
Tags: mastodon, share, publicize, crosspost, fediverse
Tested up to: 5.5
License: GNU General Public License v3.0
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Automatically share WordPress posts on Mastodon.

== Description ==
Automatically share WordPress posts on [Mastodon](https://joinmastodon.org/).

You choose which Post Types are shared—though sharing can still be disabled on a per-post basis.

Supports a number of filter hooks for developers, and Featured Images, and is fully compatible with WordPress's new block editor.

More details can be found on [this plugin's GitHub page](https://github.com/janboddez/share-on-mastodon).

== Installation ==
Within WP Admin, visit *Plugins > Add New* and search for "share on mastodon" to locate the plugin. (Alternatively, upload this plugin's ZIP file via the "Upload Plugin" button.)

After activation, head over to *Settings > Share on Mastodon* to authorize WordPress to post to your Mastodon account.

More detailed instructions can be found on [this plugin's GitHub page](https://github.com/janboddez/share-on-mastodon).

== Changelog ==
= 0.5.0 =
Support uploading of up to 4 attached images. Add additional arguments filter, e.g, for toot threading.

= 0.4.1 =
Fix `Post_Handler` actions.

= 0.4 =
Added token verification cron job.

= 0.3.1 =
Added ability to add image descriptions, improved debugging.

= 0.3 =
Allow `Post_Handler` hooks to be removed, too.

= 0.2 =
Fix `transition_post_status` parameter order.

= 0.1 =
Initial release.
