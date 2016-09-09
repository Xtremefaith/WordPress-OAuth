WordPress-OAuth
========

***IMPORTANT: WordPress-OAuth is an adapation of [Perry Butler's WP-OAuth plugin](https://github.com/perrybutler/WP-OAuth) which is available on the WordPress repository. WordPress-OAuth was originally forked to contribute updates to the WP-OAuth features and providers. Unfortunately, at this time there are many open request and no apparent support. So as of version 0.4.1, WordPress-OAuth has branched away, hoping to resurrect its development and in the end provide a better implementation of the features it provided***

![logo](http://files.glassocean.net/github/wp-oauth-logo.png)

It that allows users to login or register by authenticating with an existing Google, Facebook, LinkedIn, Github, Reddit, Office 365 or Windows Live account via OAuth 2.0. Easily drops into new or existing sites, integrates with existing users.

WordPress-OAuth functions in a similar way to the StackExchange/StackOverflow login system which allows users to register or login with the least amount of steps required.

**In this readme:** 
* [Features](#features)
* [Requirements](#requirements)
* [Quick Start](#quick-start)
* [FAQ](#faq)
* [Roadmap](#roadmap)
* [History](#history)

Features
--------
* For a list of features please see [WP-OAuth plugin](https://github.com/perrybutler/WP-OAuth) description. Here is a list of specific features and roadmap plans for WordPress-OAuth

Requirements
------------
* Requires WordPress 4.0 or higher
* Compatible up to 4.6.1

Quick Start
-----------
* Install and activate
* From the WordPress Dashboard go to **Settings** -> **WordPress OAuth** to access the settings page
* Set login options and configure at least one provider (individual instructions included)

FAQ
---
* **How is WordPress-OAuth different from WP-OAuth?**
At the moment not much. There are a few pull request on WP-OAuth that at this time are still open, but have been included in WordPress-OAuth (i.e. Matching authenticated email to WordPress user's email rather than registering a new user). Some of the first steps on the [roadmap](#roadmap) is creating a better implementation of setting up new providers for developers, (currently the implementation diverts from standard OOP approach). Also there are things within each provider that has not been accounted for as many of them appear "copy/pasted" and bare minimum. Hoping to provide a more flexible plugin that is capable of being extended much better.

Also, the codebase itself is in the process of being cleaned up and more clearly documented

* **Can I contribute?**
Please do! A big reason for the diverge to WordPress-OAuth is because although developers were contributing their contributions were not being merged. Each Pull Request should be in direct relationship to an open ticket so that details about the contribution can be discussed prior to the implementation.

Roadmap
-------
* Complete rewrite of WP-OAuth provider implementation
* Clear code documentation
* Full compabitility with WordPress Multisite, BuddyPress, bbpress.
* Icon sets for the login provider buttons.
* Ability to acquire a registering user's third-party username / nickname / email address and auto-populate the WordPress user profile. Works as an alternative to the userXX naming pattern.

History
-------
This project is a continuation of [WP-OAuth](http://github.com/perrybutler/wp-oauth).
