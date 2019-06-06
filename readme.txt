=== Hemingway Rewritten ===
Contributors: Anders Norén
Donate link:
Tags: 
Tested up to: 3.8
Stable tag: 3.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

Hemingway Rewritten

== Installation ==

1. In your admin panel, go to Appearance -> Themes and click the Add New button.
2. Click Upload and Choose File, then select the theme's .zip file. Click Install Now.
3. Click Activate to use your new theme right away.

== Frequently Asked Questions ==

= Where can I add widgets? =

Hemingway Rewritten includes four optional widget areas: a sidebar alongside your content, and three sidebars in the footer.

Configure these areas by going to Appearance → Widgets in your Dashboard.

= Does Hemingway Rewritten use featured images? =

If a Featured Image at least 1280px wide is set for a post, it will display in the header in place of your Custom Header on single posts.

= Does Hemingway Rewritten have social links? =

You can add links to a multitude of social services by following these steps:

1. Create a new Custom Menu, and assign it to the Social Links Menu location
2. Add links to each of your social services using the Links panel
3. Icons for your social links will automatically appear under the heart icon in the header

= Quick Specs (all measurements in pixels) =

1. The main column width is 676.
2. The Primary Sidebar is 286.
3. The Footer column widths will adjust depending on the number of active sidebars:
	a. 1 active = 1040
	b. 2 active = 489 each
	c. 3 active = 312 each

== Changelog ==

= 14 September 2017 =
* Add `min-width` to `ul` so box shadow extends properly

= 25 August 2017 =
* Replace line of smarter featured image code that was not compatible with PHP 5.3.x, for backwards compatibility.

= 2 August 2017 =
* fix headstart hebrew translation

= 13 July 2017 =
* Cleaning up eventbrite selectors for more specific color styles

= 27 June 2017 =
* Add hover state to social icons in new widget, remove top border

= 8 June 2017 =
* Add JavaScript resize event to fix aspect-ratio issue with video widget. Add styles for lists, and too long text in text widget.

= 25 April 2017 =
* Register the default header so it can be reapplied after being hidden; adds Smarter Featured Images support.

= 22 March 2017 =
* add Custom Colors annotations directly to the theme
* move fonts annotations directly into the theme

= 6 February 2017 =
* Replace get_the_tag_list() with the_tags() for a more straightforward approach that prevents potential fatal errors.

= 24 January 2017 =
* Adding word-wrap: break-word to the site title, to make sure longer single word titles wrap.

= 30 November 2016 =
* Fix Content Options Featured Images undeclared variable by adding extra check to make sure variable is set

= 28 November 2016 =
* Fix typo

= 24 November 2016 =
* Add support for Content Options - Featured Images

= 8 November 2016 =
* Change the content width for full-width page template to make sure galleries use all the available space.

= 3 November 2016 =
* Add Headstart translations (strand ID 8655).

= 19 October 2016 =
* Use CSS selector for Content Options

= 2 September 2016 =
* Update RTL styles to work with custom menu.

= 29 August 2016 =
* Add sub-menu indicating arrows for custom menus.

= 24 August 2016 =
* Replaces "[...]" (appended to automatically generated excerpts) with ... and a 'Continue reading' link.

= 19 August 2016 =
* Content Options, Post Details, make sure to target the "/" separating the date and the comments

= 22 July 2016 =
* Add support for Content Options

= 12 May 2016 =
* Add new classic-menu tag.

= 5 May 2016 =
* Move annotations into the `inc` directory.

= 4 May 2016 =
* Move existing annotations into their respective theme directories.

= 8 April 2016 =
* See #3786. Changes margin CSS for top posts image to be more specific, only for margin-bottom.

= 20 August 2015 =
* Add text domain and/or remove domain path. (E-I)

= 31 July 2015 =
* Remove `.screen-reader-text:hover` and `.screen-reader-text:active` style rules.

= 30 July 2015 =
* Add Editor Styles.

= 16 July 2015 =
* Always use https when loading Google Fonts. See #3221;

= 13 May 2015 =
* Remove :hover and :active states on screen-reader-text to fix IE 10/11 bug where text obscures content.

= 6 May 2015 =
* Fully remove example.html from Genericons folders.
* Remove index.html file from Genericions.

= 8 January 2015 =
* Move variable and if statement after the_post in infinite scroll render function to make it work right.

= 17 December 2014 =
* Allow tablets to access submenu items in the site navigation.

= 16 September 2014 =
* Add latin extended subset to Google Font Lato.

= 4 August 2014 =
* Set a lower z-index on the footer such that the follow box does not get covered

= 24 July 2014 =
* change theme/author URIs and footer links to `wordpress.com/themes`.

= 8 July 2014 =
* Register default header image to ensure that resetting the image to the default via the Customizer works on the front end.

= 30 June 2014 =
* Add max-width and height to images to makes them responsives.

= 27 June 2014 =
* filter content width for no-sidebar page template and one-column layout (no sidebar widgets). Closes #2508.
* when no widgets in sidebar widget area, make main content full width.

= 1 June 2014 =
* add/update pot files.

= 8 May 2014 =
* Add new style for buttons in footer and fix search input box-sizing.

= 14 April 2014 =
* Update Responsive video support

= 11 April 2014 =
* Let's add a description.

= 6 April 2014 =
* Move WordPress.com-specific style to inc/style-wpcom.css
* Add bottom margin to WordPress.com responsive video wrapper.

= 19 March 2014 =
* Minor tweaks to line height and vertical rhythm
* Move post format check within loop in single.php; improvements to vertical rhythm
* Fix image and video post formats to display properly on the blog index; update jetpack infinite scroll render to include the content-media.php reference
* Images and videos behave the same; let's change content-image to content-media and update index and single to reflect this.
* Minor style tweaks; let's make video post format behave the same as image post format
* Link post title to the first link in the post when using the Link post format

= 18 March 2014 =
* Improvements to RTL menu styles
* Minor
* Initial pass at RTL styles
* Add featured tag in place of date for sticky posts
* When one toggled item is open, close the other to prevent search from showing up behind navigation
* Style toggle search box
* Get search toggle working
* Begin implementing search toggle for mobile devices
* Ensure header does not take up so much of the screen on mobile devices.

= 17 March 2014 =
* Rename global.js to use the theme slug
* Ensure widget search button/text field are the same height in all browsers
* Ensure infinite footer is displayed on top of slideshows
* Add bottom margin to navigation
* Don't display comma separator between tags
* Ensure black box is hidden on the back end of custom header admin
* Ensure black box behind site title/description does not persist on front end when site title/description are hidden
* Add margins to headings and blockquotes
* Add margin between sidebar and footer
* Add search form to 404 page; add image post format content template; only display post/page title if one exists

= 7 March 2014 =
* Fix for inconsistent separators
* Minor stylesheet
* Form styling
* Additional padding for nested comments
* improvements to comments display;
* escape attribute correctly

= 6 March 2014 =
* Screenshot
* Minor adjustments to styles, add tags in style.css
* Clean up entry meta on formatted posts; replace single quotes with double quotes around font names for easier annotations
* Adjust margin on comments title
* Add support for featured images on Sticky posts; minor styling tweaks to widget area colors; don't display date on Sticky posts

= 5 March 2014 =
* Style mobile menu
* Improvements to widget styles; responsive styles
* Adjust contrast on navigation menu and site description; style infinite scroll older posts button; fix nested submenu arrow direction

= 3 March 2014 =
* Style comments with custom comment callback
* Add styles for wpstats smiley
* Convert to _s; allow featured header images; remove unnecessary JS; add new readme; add Genericons support.
* Delete unnecessary files

= 27 February 2014 =
* Change theme name to new name to avoid conflicts with Hemingway
* Initial commit from .org repo
