# WP Wiki Tooltip
Contributors: nida78

Tags: wiki, wikipedia, mediawiki, tooltip, tooltipster, shortcode

Requires at least: 3.0

Tested up to: 6.4.3

Stable tag: 2.0.2

Donate link: https://n1da.net/specials/wp-wiki-tooltip/spenden/

License: GPLv2 or later

Adds explaining tooltips querying their content from a MediaWiki installation, e.g. Wikipedia.org.

# Description

Adds explaining tooltips querying their content from a [MediaWiki](https://www.mediawiki.org "see MediaWiki docs") installation, e.g. [Wikipedia.org](https://www.wikipedia.org "see the well-known Wikipedia"). Therefore shortcodes can be used in Posts and Pages to mark keywords and link them to public Wiki pages. The well-known package of [Tooltipster](https://calebjacob.github.io/tooltipster/ "Tooltipster rocks :)") is used to create the nice and themable tooltips.

Main features of the current version are:

* Setup at least one wanted Wiki base and several other options at a backend page
* Integrate the Wiki tooltip in Posts and Pages using a handy popup in Gutenberg editor or simple shortcodes
* Shortcodes can be created by a [TinyMCE](https://codex.wordpress.org/TinyMCE) plugin, too

# Frequently Asked Questions

## Can I use any Wiki installation as base for my tooltips?

Sure, as long as the used installation provides an API structured like the [API of MediaWiki](https://www.mediawiki.org/wiki/API:Main_page "see API of MediaWiki") it will work perfectly. You can use one of the public Wikipedias or setup your own Wiki URL.

## Can I use several Wikis at the same time within my WordPress?

Since version 1.4.0 the plugin provides the opportunity to manage multiple Wiki URLs! The wanted Wiki can be chosen via an attribute in the shortcode.

## Am I able to style the links to Wiki pages in another way than all other links in the blog?

Yes, you can define extra CSS style properties that are used at all links to Wiki pages!

## Can I disable tooltips for mobile access?

Since version 1.7.0 you can define a minimum screen width that is necessary to show the tooltips!

## Can I use the content of a certain section instead the complete Wiki page?

Since version 1.9.0 you can request a section by its title (anchor) using an extra attribute of the shortcode (```section="anchor-of-section"```)!

# Installation

1. Find Wiki tooltip plugin in the "Add Plugins" page within your WordPress installation or Upload the Wiki tooltip plugin to your blog,
2. Activate it,
3. Create at least one Wiki base and review the global options on the settings page
4. Add some tooltips and / or shortcodes to your Posts and Pages, and
5. See nice and helpful tooltips where ever you like

# Screenshots

1. Wiki-Tooltips Settings - Base Settings (top): manage several Wiki URLs
2. Wiki-Tooltips Settings - Base Settings (bottom): set some options how to show tooltips
3. Wiki-Tooltips Settings - Error Handling: set some Error Handling options
4. Wiki-Tooltips Settings - Designs: set designs, stylings, and animations of tooltips
5. Wiki-Tooltips Settings - Thumbnails: enable and style thumbnails
6. Create tooltips in all Gutenberg rich-text components
7. Integrate the plugin by shortcodes in posts and pages, too
8. Use the [TinyMCE](https://codex.wordpress.org/TinyMCE) plugin to get help by a popup form - also available in the Gutenberg's Classic Block
9. See nice and helpful tooltips

# Changelog
The last three major releases are listed here, only. Find complete log of all changes in the [extra changelog file](https://github.com/nida78/wp-wiki-tooltip/blob/master/CHANGELOG.md)!

## [2.0.0 - C6H14N2O2 | Lysine]
*Release Date - January 3rd, 2024*

* finally, the Gutenberg editor is supported, tooltips can easily be created in every rich-text component
* content filtering of tooltips is improved especially for removing inline stylesheets

## [1.10.0 - C6H13NO2 | Leucine]
*Release Date -  December 5th, 2020*

* the backend page is splitted into several tabs to have more space for some new settings in the future
* all dynamic JavaScript code that was printed in HTML is moved into static JS files to avoid problems with other plugins
* all JavaScript is improved by removing small mistakes and minor hitches
* the used Tooltipster plugin is updated to its version 4.2.8
* some improvements for binding external resources

## [1.9.0 - C6H13NO2 | Isoleucine]
*Release Date - January 1st, 2019*

* sections of Wiki pages can be used for tooltips, now (use shortcode attribute ```section="anchor-of-section"```)
* the used Tooltipster plugin is updated to its version 4.2.6
* a new option is available to set the animation how the tooltip appears
* the new JavaScript I18N Support was implemented for the Classic-Block of Gutenberg

# Upgrade Notice

## General
You should review the settings page after every update

## Upgrade to 1.10.0
Due to the introduction of the tabbed settings page you have to review all settings after update!

## Upgrade to 1.4.0
The former Wiki URL is not transferred into this version. Review the settings page after update to insert the wanted Wiki URL again!

## Elder Upgrades
Nothing special to consider.

[2.0.0 - C6H14N2O2 | Lysine]: https://github.com/nida78/wp-wiki-tooltip/releases/tag/2.0.0
[1.10.0 - C6H13NO2 | Leucine]: https://github.com/nida78/wp-wiki-tooltip/releases/tag/1.10.0
[1.9.0 - C6H13NO2 | Isoleucine]: https://github.com/nida78/wp-wiki-tooltip/releases/tag/1.9.0
