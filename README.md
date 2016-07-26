# Multiple Domain

Multiple Domain allows you having more than one domain in a single WordPress installation. Differently than WordPress 
Multisite (MU), this plugin doesn't support a different theme or advanced customizations for each domain. It's only 
intended to enable constant navigation under a different domain than the one you set under WordPress options.

Without this plugin, if you have more than one domain set in your host, when a user access the website from a domain 
that is not the one defined in WordPress settings, all links will point to the default domain. After installing this 
plugin, you can set other domains and all links will be updated on the flow to use those domains.

This way, the user navigation will be end-to-end under the same domain.

You can also set an optional base URL. If you want to only a set of URL's to be accessed under a given domain, you can 
use this restriction.

## Installation

Follow the steps below to install the plugin:

1. Upload the plugin files to the `/wp-content/plugins/multiple-domain` directory, or install the plugin through the 
    WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Settings -> General screen to configure your additional domains

## Frequently Asked Questions

**Does this plugin set extra domains within my host?**

No. You have to set additional domains, DNS and everything to use this domain.

**Can I have a different theme/content/plugins for each domain?**

Nope. If you want a complex set up like this, you may be interested on WordPress Multisite. It's delivered with every 
WordPress installation since 3.0, you can find more info here: https://codex.wordpress.org/Create_A_Network.

## Changelog

### 0.1

This is the inital version. It supports setting domains and an optional base URL for each one.

## Meta

Contributors: gustavostraube  
Tags: multiple, domains, redirect  
Requires at least: 4.0  
Tested up to: 4.5.3  
Stable tag: trunk  
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  
