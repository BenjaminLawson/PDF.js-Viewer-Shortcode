=== PDF.js Viewer Shortcode ===
Contributors: FalconerWeb, twistermc
Tags: pdf, pdf.js, viewer, reader, embed, mozilla, shortcode
Requires at least: 4.0
Tested up to: 5.4
Stable tag: 1.4.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires PHP: 7.2

Embed a beautiful PDF viewer into pages with a simple shortcode.

== Description ==

Incorporate Mozilla's PDF.js viewer into your pages and posts with a simple shortcode. PDF.js is a javascript library for displaying pdf pages within browsers.

Features:

*   Elegant speckled gray theme
*   Customizable buttons
*   Page navigation drawer
*   Advanced search functionality
*   Language support for all languages
*   Protected PDF password entry
*   Loading bar & displays partially loaded PDF (great for huge PDFs!)
*   Document outline
*   Advanced zoom settings
*   Easy to use editor media button that generates the shortcode for you
*   Support for mobile devices

Shortcode Syntax:

`[pdfjs-viewer url=http://www.website.com/test.pdf viewer_width=600px viewer_height=700px fullscreen=true download=true print=true]`

*   `url` (required): direct url to pdf file
*   `viewer_width` (optional): width of the viewer (default: 100%)
*   `viewer_height` (optional): height of the viewer (default: 1360px)
*   `fullscreen` (optional): true/false, displays fullscreen link above viewer (default: true)
*   `download` (optional): true/false, enables or disables download button (default: true)
*   `print` (optional): true/false, enables or disables print button (default: true)

*This plugin does not support a button within the Gutenberg interface, however the shortcode still works fine.*

## Installation

This plugin can be installed either directly from your WordPress admin panel, by searching for **PDF.js Viewer Shortcode**, or downloading from the Wordpress Plugin Repository, uploading and expanding the archive into your sites `wp-content/plugins` directory.

## Changelog

### v1.4.2

* Added title to iFrame for accessibility.
* Cleaning up code per WordPress standards.

### v1.4.1

* Updating the Readme

### v1.4

* Updating to PDF.JS version v2.3.200
* Updating the Readme
* Adding Gutenberg Callout

### v1.0 - 1.3

* The birth of the plugin and first few versions.
