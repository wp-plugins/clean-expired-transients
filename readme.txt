=== Clean Expired Transients ===
Contributors: dimadin
Donate link: http://blog.milandinic.com/donate/
Tags: transient, transients
Requires at least: 3.5
Tested up to: 4.2.1
Stable tag: 1.0

Safest and simplest transients garbage collector.

== Description ==

[Plugin homepage](http://blog.milandinic.com/wordpress/plugins/clean-expired-transients/) | [Plugin author](http://blog.milandinic.com/) | [Donate](http://blog.milandinic.com/donate/)

This plugin cleans every transient from database older than one minute using safe native WordPress function. It works on multisite too.

By default, it will check for expired transients once daily, though you can call it any time using `Clean_Expired_Transients::clean();`.

Clean Expired Transients is a very lightweight, it has no settings, just activate it and it works immediately.

Note that it can be used by developers in their project in any place, it doesn't require activation and it's safe to use since it checks is there existing installation, just include it.

And it's on [GitHub](https://github.com/dimadin/clean-expired-transients).

== Installation ==

1. Upload `clean-expired-transients` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
