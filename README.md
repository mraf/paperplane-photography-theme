# Paperplane photography theme
![Paperplane photography theme](https://www.paperplanefactory.com/ppuploads/static/github/repository-open-graph-template.jpg)

## A WordPress theme for photographers
This theme is designed to enhance pictures. UX and UI elements are designed to have the least possible impact on the observation of images.


Paperplane photography theme requires [Advanced Custom Fields Pro](https://www.advancedcustomfields.com/pro/ "Advanced Custom Fields Pro") to be installed.<br/>
Required set of fields is already included through functions.php.<br/>
### :v: The main objectives of this theme are:
* display images on all devices without cropping;
* give photographers maximum editorial control;
* web performance;
* SEO friendly also if site is based mainly on images;

### :sunglasses: Features:
* dark or clear mode navigation;
* toggle all unnecessary navigation information when viewing a photo;
* sell single picture trough PayPal;
* homepage layout adjustable to show one single random picture or a list of works;
* gallery navigation is managed using the native system that WordPress uses to manage the attachments to a post;
* gallery navigation works with keyboard arrows and on mobile devices with swipe gestures;
* every image has its own URL and a set of microdata based on [schema.org ImageObject](https://schema.org/ImageObject "schema.org ImageObject");
* set custom logo for home button or just leave site title as text link;
* optional custom post types for news and books;

### :exclamation: How to set it up:
* :hankey: before activating this theme be sure to have activated Advanced Custom Fields Pro!!
* create a page and set "Home" as template;
* configure requested options;
* in WordPress "Settings > Reading" options set it as home page;
* go to "Theme settings" to set links you want to appear in footer. "Theme version" option can be useful for forcing cache clearing;
* go to "Site settings" and set both "Typographic" and "Image gallery" options;
* two menus are available: one for header and another for navigation reachable trough hamburger menu. Be sure not to add to many links in header menu because it's designed to be compact;
* if you need a news section there's a "News" custom post type for it. To add a news listing page create a new page and assign "News" as template. News published within 90 days are automatically listed in homepage;
* if you need a books section there's a "Books" custom post type for it. To add a books listing page create a new page and assign "Books" as template;
* if you want to sell an image you must first configure the basic information for PayPal and then, from the editor of the single image in the media library, enable the sale and set the price;

### :exclamation: How to set up a gallery:
Galleries use WordPress posts and post attachments. To create a gallery:
* create a new post;
* upload to the post all images you want to add to the gallery;
* eventually re-order images using WordPress media panel;
* publish post;

Don't insert pictures in content, use "the_content" to describe your project instead: navigation trough images is generated automatically.

### :electric_plug: Useful plugins to install:
* [WP Fastest Cache](https://it.wordpress.org/plugins/wp-fastest-cache/ "WP Fastest Cache") to improve loading time;
* [Contact Form 7](https://it.wordpress.org/plugins/contact-form-7/ "Contact Form 7"): CSS rules perfectly define appearence of forms created with CF7. In CF7 editor just wrap your form into a DIV with class "form-hold";
* [WebP Express](https://wordpress.org/plugins/webp-express/ "WebP Express") is a must have plugin if your hosting provider supports WebP image conversion tools;

### :sparkling_heart: Cool stuff used in this theme:
* [Swup](https://swup.js.org/ "Swup");
* [LazyLoad](https://github.com/verlok/lazyload "LazyLoad");
* [Tocca.js](https://gianlucaguarini.com/Tocca.js/ "Tocca.js");
* [Infinite Scroll](https://infinite-scroll.com/ "Infinite Scroll");

### :zap: Lighthouse report
Here's a [Lighthouse](https://developers.google.com/web/tools/lighthouse "Lighthouse") report. To do even better convert images into WebP format.
![Lighthouse report](https://www.paperplanefactory.com/ppuploads/static/github/lighthouse.png)

### :smiling_imp: Why this plugin is not on [Theme Directory](https://wordpress.org/themes/ "Theme Directory")?
I'm lazy, so instead of creating a page to manage theme's options in a traditional way, I preferred to use [Advanced Custom Fields Pro](https://www.advancedcustomfields.com/resources/including-acf-within-a-plugin-or-theme/ "Advanced Custom Fields Pro").<br />
And yes, I'm so lazy that I don't even want to sell this theme and then have to provide support.<br />
