# Awesome WP Speed Up
Plugins and resources to speed up and optimize your WordPress site.

## Table Of Contents
* [Page Caching Plugins](#page-caching-plugins)
* [Object Caching Plugins](#object-caching-plugins)
* [Fragment Caching Plugins](#fragment-caching-plugins)
* [Browser Caching Plugins](#browser-caching-plugins)
* [Minification Plugins](#minification-plugins)
* [CDN Integration Plugins](#cdn-integration-plugins)
* [Image Optimization Plugins](#image-optimization-plugins)
* [Lazy Loading Plugins](#lazy-loading-plugins)
* [Reduce HTTP Requests on Load Plugins](#reduce-http-requests-on-load-plugins)
* [Database Optimization Plugins](#database-optimization-plugins)
* [Slow Query and Debugging Plugins](#slow-query-and-debugging-plugins)
* [NGNIX and Varnish Control Plugins](#ngnix-and-varnish-control-plugins)
* [Caching Helper Plugins](#caching-helping-plugins)
* [WP-CLI Commands and Packages](#wp-cli-commands-and-packages)
* [Performance Benchmarking Sites](#performance-benchmarking-sites)
* [Load Impact Tools](#load-impact-tools)
* [New Relic Plugins](#new-relic-plugins)
* [NGNIX Configs](#ngnix-configs)
* [Apache Configs](#apache-configs)
* [Varnish Configs](#varnish-configs)
* [Further Reading](#further-reading)

## Page Caching Plugins
* [WP Fastest Cache](https://wordpress.org/plugins/wp-fastest-cache/) - This plugin creates static html files from your dynamic WordPress blog.
* [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/) - This plugin generates static html files from your dynamic WordPress blog. After a html file is generated your webserver will serve that file instead of processing the comparatively heavier and more expensive WordPress PHP scripts.
* [Comet Cache](https://wordpress.org/plugins/comet-cache/) - If you care about the speed of your site, Comet Cache is one of those plugins that you absolutely MUST have installed Comet Cache takes a real-time snapshot (building a cache) of every Page, Post, Category, Link, etc. 
* [Cache Enabler](https://wordpress.org/plugins/cache-enabler/) - The Cache Enabler plugin creates static HTML files and stores them on the servers disk.
* [SG Optimizer](https://wordpress.org/plugins/sg-cachepress/) - This plugin is designed to link WordPress with the SiteGround Performance services.
* [WP Rocket](https://wp-rocket.me/) - Your website at lightspeed.
* [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/) - The highest rated and most complete WordPress performance plugin. Dramatically improve the speed and user experience of your site. Add browser, page, object and database caching as well as minify and content delivery network (CDN) to WordPress.
* [Cachify](https://wordpress.org/plugins/cachify/) - Cachify optimizes your page loads by caching posts, pages and custom post types as static content.
* [Hyper Cache](https://wordpress.org/plugins/hyper-cache/) - Hyper Cache is a cache plugin specifically written to get the maximum speed for your WordPress site.
* [Powered Cache](https://wordpress.org/plugins/powered-cache/) - Comprehensive caching and performance plugin for WordPress.
* [Redis Page Cache for WordPress](https://github.com/pressjitsu/pj-page-cache-red) - A Redis-backed full page caching plugin for WordPress, extremely flexible and fast. Requires a running Redis server and the PHP Redis PECL extension.
* [Varnish Caching](https://github.com/razvanstanga/varnish-caching-wordpress-plugin) - Complete Wordpress Varnish Cache 3.x/4.x integration.
* [Breeze](https://wordpress.org/plugins/breeze/) - Breeze is a WordPress cache plugin with extensive options to speed up your website. All the options including Varnish Cache are compatible with Cloudways hosting.
* [Pantheon Advanced Page Cache](https://wordpress.org/plugins/pantheon-advanced-page-cache/) - Automatically clear related pages from Pantheon's Edge when you update content. High TTL. Fresh content. Visitors never wait.
* [LiteSpeed Cache](https://wordpress.org/plugins/litespeed-cache/) - WordPress plugin to connect to LSCache on LiteSpeed Web Server.
* [Pegasaas Accelerator WP](https://wordpress.org/plugins/pegasaas-accelerator-wp/) - The Pegasaas Accelerator WP plugin interfaces with the Pegasaas API to optimize a website for Web Perormance and Google PageSpeed.
* [NitroPack](https://wordpress.org/plugins/nitropack/) - A site performance optimization plugin.
* [ezCache](https://wordpress.org/plugins/ezcache/) - EzCash is an easy and innovative cache plugin that will help you significantly improve your site speed.
* [Surge](https://wordpress.org/plugins/surge/) - A fast and simple page caching plugin for WordPress.
* [SpeedyCache](https://wordpress.org/plugins/speedycache/) - SpeedyCache is a plugin that helps you reduce the load time of your website by means of caching, minification, and compression of your website.

## Object Caching Plugins
* [Object Cache Pro](https://objectcache.pro/?ref=luke) - A business class Redis object cache backend for WordPress.
* [Redis Object Cache](https://wordpress.org/plugins/redis-cache/) - A persistent object cache backend powered by Redis. Supports Predis, PhpRedis (PECL), HHVM, replication, clustering and WP-CLI. 
* [Tiny Cache](https://github.com/szepeviktor/tiny-cache) - Cache post content, translations and nav menu output in persistent object cache.
* [Docket Cache](https://wordpress.org/plugins/docket-cache/) - A file-based persistent WordPress Object Cache stored as a plain PHP code.
* [Memcached Redux](https://wordpress.org/plugins/memcached-redux/) - Changes the famous Memcached WP Object Cache backend to actually use the Memcached class (not the Memcache class).
* [WP Redis](https://wordpress.org/plugins/wp-redis/) - For sites concerned with high traffic, speed for logged-in users, or dynamic pageloads, a high-speed and persistent object cache is a must.

## Fragment Caching Plugins
* [Fragment Cache](https://github.com/Rarst/fragment-cache) - Fragment Cache is a WordPress plugin for partial and async caching of heavy front-end elements. It currently supports caching navigation menus, widgets, and galleries.
* [PJ Fragment Cache](https://github.com/pressjitsu/fragment-cache) - Fragment caching with storage support for transients, object cache and object metadata.

## Browser Caching Plugins
* [Speed Up – Browser Caching](https://wordpress.org/plugins/speed-up-browser-caching/) - This small plugin (10 Kb) enables browser caching in your Apache web server and help browser to cache a local copy of static files and improve page load times. 
* [WP Performance Score Booster](https://wordpress.org/plugins/wp-performance-score-booster/) - This plugin speed-up page load times and improve website scores in services like PageSpeed, YSlow, Pingdom and GTmetrix.

## Minification Plugins
* [Autoptimize](https://wordpress.org/plugins/autoptimize/) - Autoptimize makes optimizing your site really easy. It concatenates all scripts and styles, minifies and compresses them, adds expires headers, caches them, and moves styles to the page head and can move scripts to the footer.
* [Autoptimize criticalcss.com power-up](https://wordpress.org/plugins/autoptimize-criticalcss/) - Let Autoptimize and CriticalCSS unleash your site performance and make it appear better than anyone in search results.
* [WP Roids](https://wordpress.org/plugins/wp-roids/) - Fast AF caching! Plus minifies your site’s HTML, CSS & Javascript.
* [Merge + Minify + Refresh](https://wordpress.org/plugins/merge-minify-refresh/) - Merge/Concatenate & Minify CSS & JS.
* [Minify HTML](https://www.littlebizzy.com/plugins/) - Tactfully minifies HTML output and markup to remove line breaks, whitespace, comments, and other code bloat to cleanup source code and improve speed.
* [RapidLoad Power-Up for Autoptimize](https://wordpress.org/plugins/unusedcss/) - Makes your site even faster and lighter by automatically removing Unused CSS from your website.
* [Torque](https://wordpress.org/plugins/torque/) - Make your Wordpress website noticably faster by optimising how it is delivered. Analyse your website's performance and security, minify and combine your assets, and configure an array of performance and security settings quickly and easily with this comprehensive plugin. Achieves the best compression of any minification.
* [SCSS WP Editor](https://wordpress.org/plugins/scss-wp-editor/) - WP SCSS Editor will provide you to add SCSS from your WordPress admin. You just need to add your SCSS and save it.
* [ShortPixel Critical CSS](https://wordpress.org/plugins/shortpixel-critical-css/) - Use ShortPixel's Critical CSS web service to automatically create the required CSS for above the fold.

## CDN Integration Plugins
* [CDN Enabler](https://wordpress.org/plugins/cdn-enabler/) - A content delivery network (CDN) is a network of distributed edge servers, which accelerate your content around the globe. The main benefits of a CDN are scalability, reliability and performance.
* [Cloudflare](https://wordpress.org/plugins/cloudflare/) - The easiest way to setup Cloudflare for your WordPress site.
* [Cloudflare Page Cache](https://wordpress.org/plugins/cloudflare-page-cache/) - Cache HTML pages on the Cloudflare CDN when used with the page cache Worker.
* [Fastly](https://wordpress.org/plugins/fastly/) - Using this plugin means you won’t have to purge content in Fastly when you make changes to your WordPress content. Purges will automatically happen with no need for manual intervention.
* [Cloudinary](https://wordpress.org/plugins/cloudinary-image-management-and-manipulation-in-the-cloud-cdn/) - With Cloudinary, all your images are automatically uploaded, normalized, optimized and backed-up in the cloud instead of being hosted on your servers.
* [Photon](https://jetpack.com/support/photon/) - Photon is an image acceleration and editing service for sites hosted on WordPress.com or on Jetpack-connected WordPress sites. That means less load on your host and faster images for your readers.
* [ILAB Media Tools](https://en-ca.wordpress.org/plugins/ilab-media-tools/) - ILAB Media Tools are a suite of tools designed to enhance media handling in WordPress in a number of ways.
* [WP Offload S3](https://deliciousbrains.com/wp-offload-s3/) - ILAB Media Tools are a suite of tools designed to enhance media handling in WordPress in a number of ways.
* [DADI CDN](https://github.com/dadi/cdn) - A self-hosted, just-in-time asset manipulation and delivery application, providing a complete content distribution/delivery solution.
* [Tachyon](https://github.com/humanmade/tachyon-plugin) - Tachyon is an image resizing processor built to be used withaccelerates your WordPress website Amazon S3 as the image backend, and sits behind a CDN such as CloudFlare.
* [CDN Linker](https://github.com/wmark/CDN-Linker) - Modifies links pointing to <code>wp-content</code> and/or <code>wp-includes</code> (or whatever you configure) by replacing your ‘blog_url’ with a custom one. Enables you to pull static files, such as images, CSS or JS, from a different host, mirror or CDN.
* [C3 Cloudfront Cache Controller](https://wordpress.org/plugins/c3-cloudfront-clear-cache/) - This is simple plugin that clear all cloudfront cache if you publish posts.
* [Beaver Builder + Amazon S3](https://github.com/liquidweb/beaverbuilder-s3) - Ensures compatibility between Beaver Builder and Human Made's S3 Uploads plugin.
* [WP-Stateless](https://wordpress.org/plugins/wp-stateless/) - Stores and serves WordPress media files directly from Google Cloud Storage.
* [WP Azure offload](https://wordpress.org/plugins/wp-azure-offload/) - Automatically copies media to Azure storage and deliver using CDN.
* [CloudFlare](https://www.littlebizzy.com/plugins) - Easily connect your WordPress website to CloudFlare's free optimization features, including one-click options to purge cache and enable 'dev' mode.
* [WordPress CDN and Image Hosting Plugin – Sirv](https://wordpress.org/plugins/sirv/) - Instantly resize or crop images to any size. Add watermarks, titles, text and image effects. Embed them as images, galleries, zooms or 360 spins. Serve them from the fast CDN. Responsive, to perfectly fit the screen. Use the "Add Sirv Media" button on posts and pages.
* [Google Cloud CDN Page Cache](https://wordpress.org/plugins/gc-page-cache-cdn/) - Low cost and high performance international page cache based on Google Cloud CDN.
* [WP Godspeed – One click CDN](https://wordpress.org/plugins/wp-godspeed/) - The premiere free CDN plugin for WordPress.
* [Cloudflare Stream Video](https://wordpress.org/plugins/cloudflare-stream/) - Cloudflare Stream Video is an easy-to-use, affordable, on-demand video streaming platform. Stream seamlessly integrates video storage, encoding, and a customizable player with Cloudflare's fast, secure, and reliable global network, so that you can spend less time managing video delivery and more time building and promoting your product.
* [WP Cloudflare Super Page Cache](https://wordpress.org/plugins/wp-cloudflare-page-cache/) - Speed up your website by enabling page caching on Cloudflare on free plans.
* [QuantCDN](https://wordpress.org/plugins/quant/) - QuantCDN static edge integration.
* [TwicPics](https://wordpress.org/plugins/twicpics/) - TwicPics is a real-time image processing service that enables individuals and businesses of all sizes to deliver high performing and rich visual content with easy setup.
* [Amazon AWS CDN](https://wordpress.org/plugins/aws-cdn-by-wpadmin/) - Setup Amazon Cloudfront CDN for your website. Now with intuitive layout and more flexibility. Also supports WordPress Multisite installation.
* [RocketCDN](https://wordpress.org/plugins/rocketcdn/) - RocketCDN automatically rewrites all URLs to be served by our content delivery network (CDN). Easy CDN deployment to WordPress.
* [Replace Google Fonts with Bunny Fonts](https://wordpress.org/plugins/replace-google-fonts-with-bunny-fonts/) - Easily replace Google Fonts with Bunny Fonts.
* [FastPixel Website Accelerator](https://wordpress.org/plugins/fastpixel-website-accelerator/) - Faster WordPress made easy - the latest technology to speed up your website, packaged in a 1-minute setup plugin.

## Image Optimization Plugins
* [EWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/) - The EWWW Image Optimizer is a WordPress plugin that will automatically optimize your images as you upload them to your blog.
* [EWWW Image Optimizer Cloud](https://wordpress.org/plugins/ewww-image-optimizer-cloud/) - The EWWW Image Optimizer is a WordPress plugin that will automatically optimize your images as you upload them to your blog.
* [TinyPNG](https://wordpress.org/plugins/tiny-compress-images/) - Make your website faster by optimizing your JPEG and PNG images. This plugin automatically optimizes all your images by integrating with the popular image compression services TinyJPG and TinyPNG.
* [Imagify](https://wordpress.org/plugins/imagify/) - Speed up your website with lighter images without losing quality.
* [ImageRecycle](https://wordpress.org/plugins/imagerecycle-pdf-image-compression/) - ImageRecycle is an automatic Image and PDF content optimizer for WordPress website.
* [ShortPixel Image Optimizer](https://wordpress.org/plugins/shortpixel-image-optimiser/) - Increase your website’s SEO ranking, number of visitors and ultimately your sales by optimizing any image or PDF document on your website.
* [Kraken.io](https://wordpress.org/plugins/kraken-image-optimizer/) - This plugin allows you to optimize and resize new and existing WordPress image uploads through Kraken.io Image Optimizer’s API.
* [Optimus](https://wordpress.org/plugins/optimus/) - Optimus reduces the file size of uploaded media files automatically. Depending on the image and format, reductions in size of up to 70% are possible.
* [Image Compression and optimization](https://wordpress.org/plugins/wp-image-compression/) - Optimize your Images as well as Image Compression of upto 80%. Also resize images on upload to help reduce storage and bandwidth before compressing.
* [Media Cleaner](https://wordpress.org/plugins/media-cleaner/) - Clean your Media Library from the media which aren’t used in any of your posts, gallery and so on.
* [ImageLint](https://github.com/imagelint/imagelint-wordpress) - One-stop hassle-free no-config ImageLint WordPress integration.
* [FAF Optim](https://github.com/fafiebig/faf-optim) - Optimize images of your WordPress media storage.
* [Media Deduper](https://wordpress.org/plugins/media-deduper/) - Save disk space and bring some order to the chaos of your media library by removing and preventing duplicate files.
* [WP Smush](https://wordpress.org/plugins/wp-smushit/) - Reduce image file sizes, improve performance and boost your SEO using the free WordPress Smush API.
* [WP Google PageSpeed Image Optimizer Lite](https://wordpress.org/plugins/wp-google-pagespeed-image-optimizer-lite/) - This plugin will optimize your images exactly like Google Pagespeed Insights.
* [Image Optimizer WD – WordPress Image Optimizer](https://wordpress.org/plugins/image-optimizer-wd/) - Image Optimizer WordPress plugin enables you to resize, compress and optimize PNG, JPG, GIF files while maintaining image quality.
* [WP Compress - Image Optimizer](https://wordpress.org/plugins/wp-compress-image-optimizer/) - Compress and optimize images to shrink file size, improve load times and boost PageSpeed scores in just one click using WP Compress image optimization.
* [Auto Cloudinary](https://wordpress.org/plugins/auto-cloudinary/) - Super simple Cloudinary auto-upload implementation for WordPress.
* [Fly Dynamic Image Resizer](https://wordpress.org/plugins/fly-dynamic-image-resizer/) - Dynamically create image sizes on the fly.
* [Autoremove Attachments](https://wordpress.org/plugins/autoremove-attachments/) - Autoremove Attachments helps you keep your media library clean by deleting all media files attached to a post when that post is permanently removed from your system.
* [Dynamic Image Resizer](https://github.com/RadoslavGeorgiev/dynamic-image-resizer) - Generates image sizes only when needed, instead of the 404 page.
* [Image Optimize Command](https://github.com/TypistTech/image-optimize-command) - Easily optimize images using WP CLI.
* [tiny.pictures Image CDN](https://wordpress.org/plugins/tiny-pictures-image-cdn/) - Scales and optimizes your images using the tiny.pictures image processing service in the cloud and delivers them through worldwide CDN nodes.
* [Piio – Powerful Image Compressor, Optimization and Delivery](https://wordpress.org/plugins/piio-image-optimization/) - Generates responsive and optimized images, so you don't have to.
* [Resize Image After Upload](https://wordpress.org/plugins/resize-image-after-upload/) - Automatically resize uploaded images to within specified maximum width and height. Also has option to force recompression of JPEGs.
* [Image optimization & Lazy Load by Optimole](https://wordpress.org/plugins/optimole-wp/) - Complete handling of your website images.
* [MegaOptim Image Optimizer](https://wordpress.org/plugins/megaoptim-image-optimizer/) - MegaOptim is image compression plugin that optimizes your images in the cloud using intelligent image compression methods to save as much space as possible while keeping the quality almost identical. It's compatible with NextGen Gallery, MediaPress, WP Retina 2x and many other gallery plugins.
* [Stop Generating Image Sizes](https://wordpress.org/plugins/image-sizes/) - So, it creates multiple sizes of an image while uploading? Here is the solution.
* [ShortPixel Adaptive Images](https://wordpress.org/plugins/shortpixel-adaptive-images/) - Display properly sized, smart cropped and optimized images on your website. Images are processed on the fly and served from our CDN.
* [Pixelerate Image CDN](https://wordpress.org/plugins/pixelerate-cdn/) - Integrate the Pixelerate Image Optimization and CDN into your WordPress website.
* [Warp iMagick](https://wordpress.org/plugins/warp-imagick/) - Optimize (jpeg) media images/thumbnails to reduce file size.
* [WebP Express](https://wordpress.org/plugins/webp-express/) - Serve autogenerated WebP images instead of jpeg/png to browsers that supports WebP. Works on anything (media library images, galleries, theme images etc).
* [Robin image optimizer](https://wordpress.org/plugins/robin-image-optimizer/) - Optimize images without losing quality, speed up your website load, improve SEO and save money on server and CDN bandwidth.
* [Crush.pics – Image Compression and Optimization](https://wordpress.org/plugins/crush-pics/) - Image Compression and Optimization using Crush.pics API.
* [Image CDN – WordPress CDN Plugin](https://wordpress.org/plugins/image-cdn/) - Optimize your WordPress site with ImageEngine or another Image CDN (or any other Content Delivery Network).
* [Abraia](https://wordpress.org/plugins/abraia/) - Bulk optimize your Wordpress images with Abraia.
* [CompressWP](https://wordpress.org/plugins/compresswp-optimize-and-compress-jpeg-and-png-images/) - Optimize JPEG and PNG images to significantly improve your page load speeds.
* [NutsForPress Images and Media](https://wordpress.org/plugins/nutsforpress/) - NutsForPress Images and Media is an essential companion for having your images and your meta in perfect order. Images and Media automatically resizes images, compresses JPGs, bulk rebuilds thumbnails and PDF previews, writes automatically and bulk rewrites your attachments meta.
* [Giga WebP Image Converter](https://wordpress.org/plugins/giga-webp-image-converter/) - Convert images with ease for free: reduce image sizes without deleting the originals. Improve Google Site Speed Score and SEO.
* [WPvivid Imgoptim](https://wordpress.org/plugins/wpvivid-imgoptim/) - Optimize, compress and resize images in WordPress in bulk. Automatic image optimization, auto resize images upon upload.
* [External Images](https://www.wpintense.com/product/external-images/) - This plugin alters WordPress and WooCommerce to allow you to use images hosted anywhere on the internet, rather than having to have images hosted on your own server.
* [OptiPic images optimization](https://wordpress.org/plugins/optipic/) - OptiPic.io - image optimization via smart CDN. The module automates the process of optimizing and compressing all images on the site according to the recommendations of Google PageSpeed Insights.
* [Image Regenerate & Select Crop](https://wordpress.org/plugins/image-regenerate-select-crop/) - Regenerate and crop images, details and actions for image sizes registered and image sizes generated, clean up, placeholders, custom rules, register new image sizes, crop medium settings, WP-CLI commands, optimize images.
* [Preload Featured Images](https://wordpress.org/plugins/preload-featured-images/) - Preload featured images in single post to get higher PageSpeed Score.
* [Modern Images WP](https://wordpress.org/plugins/modern-images-wp/) - Choose a default format for subsized images. Choose WebP, JPGXL or AVIF when your server image library supports them.
* [Compress Images with Squeezeimg](https://wordpress.org/plugins/compress-images-with-squeezeimg/) - The "Compress Images with Squeezeimg" plugin helps to optimize all your images and improve the performance of your website.
* [reSmush.it Image Optimizer](https://wordpress.org/plugins/resmushit-image-optimizer/) - Image Optimization API. Provides image size optimization.
* [Aspose Image Optimizer](https://wordpress.org/plugins/aspose-image-optimizer/) - Optimizes images inside the WordPress directory and its sub-directories.
* [Quicq for WebP images](https://wordpress.org/plugins/quicq/) - Quicq integration for Wordpress.
* [Converter for Media – Optimize images | Convert WebP & AVIF](https://wordpress.org/plugins/webp-converter-for-media/) - Speed up your website using our ease image optimizer by serving WebP and AVIF images.
* [Imsanity](https://wordpress.org/plugins/imsanity/) - Automatically resize huge image uploads with Imsanity. 
* [Avif Express](https://wordpress.org/plugins/avif-express/) - Converts Images to AVIF.
* [AVIF Support](https://wordpress.org/plugins/avif-support/)) - AVIF support plugin aims to support avif images in WordPress by overcome wp issues and limits regarding uploading, displaying and generating avif images.

## Lazy Loading Plugins
* [Rocket Lazy Load](https://wordpress.org/plugins/rocket-lazy-load/) - Lazy Load displays images on a page only when they are visible to the user. This reduces the number of HTTP requests mechanism and improves the loading time.
* [Lazy Load for Videos](https://wordpress.org/plugins/lazy-load-for-videos/) - This plugin improves page load times and increases your Google PageSpeed Score. It replaces embedded Youtube and Vimeo videos with a clickable preview image.
* [Disqus Conditional](https://wordpress.org/plugins/disqus-conditional-load/) - DCL is an advanced version of Disqus Commenting System, with which experience the boosted page loading speed difference. 
* [Lazy Facebook Comments](https://wordpress.org/plugins/lazy-facebook-comments/) - Use Facebook comments system in your website without slowing down your website. 
* [Lazy Load for Comments](https://wordpress.org/plugins/lazy-load-for-comments/) - Lazy load WordPress default commenting system without any complex configurations.
* [WordPress Image Preload](https://github.com/aderaaij/wp-image-preload) - A modern lazyload / image preload plugin based on Intersection Observer.
* [Flying Images](https://wordpress.org/plugins/nazy-load/) - High-performance Native Image Lazy Loading.
* [reGenerate Thumbnails Advanced](https://wordpress.org/plugins/regenerate-thumbnails-advanced/) - Regenerate thumbnails fast and easy while removing unused thumbnails of existing images; very useful when changing a theme.
  
## Reduce HTTP Requests on Load Plugins
* [Disable Emoji](https://wordpress.org/plugins/disable-emojis/) - This plugin disables the new WordPress emoji functionality.
* [Disable Emojis](https://www.littlebizzy.com/plugins) - Completely disables both the old and new versions of WordPress emojis, removes the corresponding javascript calls, and improves page loading times.
* [Emoji Settings](https://wordpress.org/plugins/emoji-settings/) - Emoji Settings adds an option within your Writing Settings page to disable or enable emojis.
* [Compressed Emoji](https://wordpress.org/plugins/compressed-emoji/) - WordPress emoji comes from s.w.org and they are not optimized well, Compressed Emoji fixes this problem.
* [Disable Embeds](https://wordpress.org/plugins/disable-embeds/) - Disable Embeds
* [Plugin Organizer](https://wordpress.org/plugins/plugin-organizer/) - This plugin allows you to do the following, change the order that your plugins are loaded,selectively disable plugins by any post type or wordpress managed URL and adds grouping to the plugin admin age.
* [WP Asset CleanUp](https://wordpress.org/plugins/wp-asset-clean-up/) - There are often times when you are using a theme and a number of plugins which are enabled and run on the same page.
* [WP Disable](https://wordpress.org/plugins/wp-disable/) - Reduce HTTP requests - Disable Emojis, Disable Gravatars, Disable Embeds and Remove Querystrings. Added support to disable pingbacks, disable trackbacks, close comments after 28 days, Added the ability to force pagingation after 20 posts, Disable WooCommerce scripts and CSS on non WooCommerce Pages, Disable RSS, Disable XML-RPC, Disable Autosave, Remove Windows Live Writer tag, Remove Shortlink Tag, Remove WP API from header.
* [Complete Analytics Optimization Suite (CAOS)](https://wordpress.org/plugins/host-analyticsjs-local/) - Only load scripts and styles if a specific shortcode is present in the content when the page/post is saved.
* [Gonzales](https://tomasz-dobrzynski.com/wordpress-gonzales) - This plugin allows you to get rid of CSS and JavaScript files that are simply useless. Less is better, right? One of the biggest problem of modern websites is page weight.
* [Code Snippets WP Speed Up](https://github.com/lukecav/code-snippets-wp-speed-up) - Code Snippets for WordPress speed up which can be imported into the plugin.
* [WP Head Optimizer](https://wordpress.org/plugins/wp-head-optimizer/) - This plugin allow you to remove unnecessary tags, urls, scrips and manymore additional things from your WordPress header to speed up site loading time and hide some details form visitors for security purpose.
* [Machete](https://wordpress.org/plugins/machete/) - Machete is a lean and simple suite of tools that solve common WordPress anoyances: cookie bar, tracking codes, header cleanup.
* [Disable User Gravatar](https://wordpress.org/plugins/disable-user-gravatar/) - Stops wordpress from automatically grabbing the users' gravatar with their registered email.
* [Disable Author Pages](https://github.com/staude/disable-author-pages/) - Disable the author pages in WordPress and redirect to the homepage.
* [Complete Analytics Optimization Suite (CAOS)](https://wordpress.org/plugins/host-analyticsjs-local/) - A plugin that allows you to completely optimize Google Analytics for your Wordpress Website: host analytics.js locally, keep it updated using wp_cron(), anonymize IP, disable tracking of admins, place tracking code in footer, and more.
* [Cache External Scripts](https://wordpress.org/plugins/cache-external-scripts/) - This plugin allows you to cache the Google Analytics JavaScript file to be cached for more than 2 hours.
* [WordPress WPO Tweaks](https://wordpress.org/plugins/wpo-tweaks/) - Several WPO Optimisations to Speed Up WordPress and get better results in Google PageSpeed, GTMetrix and Pingdom Tools.
* [Webcraftic Disable Comments](https://wordpress.org/plugins/comments-plus/) - Allows administrators to globally disable comments on their site. Comments can be disabled for individual record types.
* [Webcraftic Clearfy - disable unused features](https://wordpress.org/plugins/clearfy/) - Disables unused Wordpress features, improves performance and increases SEO rankings, using Clearfy, which makes WordPress very easy.
* [Remove Emoji Styles & Scripts](https://wordpress.org/plugins/remove-emoji-styles-scripts/) - If you do not want or need Emoji it is best to remove/dequeue Emoji styles and scripts for better performance.
* [Native Performance](https://wordpress.org/plugins/native-performance/) - Native Performance is an all-in-one complement that integrates, in a complete and robust core, a set of tools for the solution of common errors, optimization, performance and much more.
* [Disable WordPress Events and News Dashboard Widget](https://wordpress.org/plugins/disable-events-and-news-dashboard-widget/) -  Disable WordPress Events and News widget from the dashboard.
* [Dismiss "Welcome" Nag Dashboard Widget](https://wordpress.org/plugins/dismiss-welcome-nag/) -  Dismiss Welcome Panel nag, dashboard widget, when is activated, or automatically, if it is in mu-plugins directory.
* [Webcraftic Assets Manager](https://wordpress.org/plugins/gonzales/) -  Increase the speed of the pages by disabling unused scripts (.JS) and styles (.CSS). Make your website reactive.
* [WP Widget Disable](https://wordpress.org/plugins/wp-widget-disable/) -  Disable Sidebar and Dashboard Widgets with an easy to use interface. Simply use the checkboxes provided under <strong>Appearance -> Disable Widgets</strong> and select the Widgets you'd like to hide.
* [WP YouTube Video Optimizer](https://wordpress.org/plugins/wp-youtube-video-optimizer/) -  Embed multiple YouTube videos using a simple shortcode.
* [Scripts To Footer](https://wordpress.org/plugins/scripts-to-footerphp/) -  Moves scripts to the footer to decrease page load times, while keeping stylesheets in the header. Requires that plugins and theme correctly utilizes wp_enqueue_scripts hook. Can be disabled via a checkbox on specific pages and posts.
* [Speed Demon](https://www.littlebizzy.com/plugins) -  A powerful bundle of lightweight tools and settings that drastically improve the loading speed of WordPress by reducing bulk and improving efficiency.
* [Self-Hosted Google Fonts](https://wordpress.org/plugins/selfhost-google-fonts/) -  Automatically self-host your Google Fonts - works with any theme or plugin.
* [Redirect Gravatar requests](https://wordpress.org/plugins/redirect-gravatar-requests/) -  All requests to load an avatar from gravatar.com are redirected to a local image, preventing Gravatar from potentially gathering data about your site's visitors.
* [Speed Booster Pack](https://wordpress.org/plugins/speed-booster-pack/) -  Speed Booster Pack helps you improve your page loading speed and get higher scores on speed test services like GTmetrix, Google PageSpeed or WebPageTest.
* [Better Speed](https://wordpress.org/plugins/better-speed/) -  Improve the loading speed of your website by removing bloat and unused features.
* [WP Toolbelt](https://wordpress.org/plugins/wp-toolbelt/) -  More features, fast.
* [Optenhanse](https://wordpress.org/plugins/wp-plc-swissknife/) -  A unique plugin for Optimizing, Enhancing and Securing your WordPress website.
* [Flying Scripts by WP Speed Matters](https://wordpress.org/plugins/flying-scripts/) -  Flying Scripts by WP Speed Matters.
* [Speed Booster By Melotheme](https://wordpress.org/plugins/speed-booster-by-melotheme/) -  Easy WordPress website Speed & Performance optimization with one click.
* [WP Utility and Performance](https://wordpress.org/plugins/wp-utility-and-performance/) -  Allows you to remove unused resources and improve speed and performance of your WordPress website.
* [Freesoul Deactivate Plugins](https://wordpress.org/plugins/freesoul-deactivate-plugins/) -  Freesoul Deactivate Plugins allows you to disable specific plugins on specific pages. Useful to reach excellent performance and for support in problem-solving even when many plugins are active.
* [Local Gravatars](https://wordpress.org/plugins/local-gravatars/) -  Locally host gravatars - for the privacy concious.
* [Flying Fonts by WP Speed Matters](https://wordpress.org/plugins/flying-fonts/) -  Remove Google Fonts and Use System Fonts.
* [AutoTweaks](https://wordpress.org/plugins/autotweaks/) -  AutoTweaks configures a series of default options to WordPress.
* [WP Inline Cacher](https://wordpress.org/plugins/wp-inline-cacher/) -  Speed up your website by automatically inlining your stylesheets for first-time visitors.
* [Plugin Optimizer](https://wordpress.org/plugins/plugin-optimizer/) -  The Most Powerful Performance Plugin for WordPress is now available for FREE.
* [SpeedPlus OptiMini](https://wordpress.org/plugins/speedplus-optimini/) -  Increase PageSpeed score and make your site much faster. Go to WP Dashboard => Settings => SpeedPlus OptiMini.
* [Goon - Control your plugins](https://wordpress.org/plugins/goon-plugin-control/) -  The Most Powerful Performance Plugin for WordPress.
* [Wowholic CORE](https://wordpress.org/plugins/wowholic-core/) -  Utility functions and options for common tasks in WordPress.
* [Unbloater](https://wordpress.org/plugins/unbloater/) -  Remove unnecessary code, nags and bloat from WordPress core and certain plugins.
* [Easy Speed Optimizer](https://wordpress.org/plugins/easy-speed-optimizer/) -  This plugin removes redundant scripts from the pages and optimizes them.
* [WPControl](https://wordpress.org/plugins/wpcontrol/) -  The all in one plugin to optimize your WordPress website.
* [Ajax Press](https://wordpress.org/plugins/ajax-press/) -  Easily Enable Fast Ajax Navigation. Loads content without page reload.
* [Speed Booster for Elementor](https://wordpress.org/plugins/speed-booster-for-elementor/) -  Speed Booster for Elementor - optimize the loading of Elementor page builder.
* [FlashSpeed](https://wordpress.org/plugins/flashspeed/) -  FlashSpeed makes your site lightning fast by disabling unused assets and optimizing resources.
* [WP Blast](https://wordpress.org/plugins/wpblast/) -  Improve your Wordpress SEO and performance by using dynamic rendering. Prerender your website and generate an easy-to-crawl website.
* [Booster Sweeper](https://wordpress.org/plugins/booster-sweeper/) -  Booster Sweeper helps you to optimize the Website speed further over the common caching and code minification plugins.
* [Falcon](https://wordpress.org/plugins/falcon/) -  WordPress optimizations & tweaks.
* [Admin Speedo](https://wordpress.org/plugins/admin-speedo/) -  Speed-up your slow WordPress Admin Dashboard with one click. Just activate it, and your admin panel will be boosted.

## Database Optimization Plugins
* [WP-Optimize](https://wordpress.org/plugins/wp-optimize/) - WP-Optimize is an effective tool for automatically cleaning your WordPress database so that it runs at maximum efficiency.
* [WP-Sweep](https://wordpress.org/plugins/wp-sweep/) - WP-Sweep allows you to clean up unused, orphaned and duplicated data in your WordPress. It also optimizes your database tables.
* [Optimize Database after Deleting Revisions](https://wordpress.org/plugins/rvg-optimize-database/) - Host your Google Analytics javascript-file (analytics.js) locally and keep it updated using wp_cron().
* [Plugins Garbage Collector](https://wordpress.org/plugins/plugins-garbage-collector/) - Plugins Garbage Collector scans your WordPress database and shows the tables beyond of core WordPress installation.
* [Delete Expired Transients](https://wordpress.org/plugins/delete-expired-transients/) - Delete old, expired transients from WordPress wp_options table.
* [Advanced Database Cleaner](https://wordpress.org/plugins/advanced-database-cleaner/) - Clean database by deleting unused data such as 'old revisions', 'old drafts', 'orphan options', etc. Optimize database and more.
* [Transient Cleaner](https://wordpress.org/plugins/artiss-transient-cleaner/) - Housekeep expired transients from your options table.
* [Servebolt Optimizer](https://wordpress.org/plugins/servebolt-optimizer/) - A plugin that checks and implements Servebolt Performance best practises for WordPress.
* [Delete Expired Transients](https://www.littlebizzy.com/plugins) - Deletes all expired transients upon activation and on a daily basis thereafter via WP-Cron to maintain a cleaner database and improve performance.
* [Yoast SEO Cleaner](https://wordpress.org/plugins/wps-cleaner/) - WPS Cleaner cleans the database and WordPress.
* [Custom Post Type Cleanup](https://wordpress.org/plugins/custom-post-type-cleanup/) - Detect and delete posts from custom post types that are no longer in use.
* [Scalability Pro](https://www.wpintense.com/product/scalability-pro/) - The Scalability Pro Plugin is the core WP Intense plugin to transform the speed and scalability of your WordPress site. It does so primarily by eliminating table scans and using index seeks instead.
* [Index WP MySQL For Speed](https://wordpress.org/plugins/index-wp-mysql-for-speed/) - Add useful indexes to your WordPress installation's MySQL database.
* [SweepPress](https://wordpress.org/plugins/sweeppress/) - Remove various old, unused or obsolete data from the database, optimize the database for best performance.
* [Index WP Users For Speed](https://wordpress.org/plugins/index-wp-users-for-speed/) - Index WP Users For Speed.
* [Templ Optimizer](https://wordpress.org/plugins/templ-optimizer/) - An easy-to-use optimization plugin that lets you clean your database and tweak various performance related settings on your WordPress site.
* [Performance Tweaks](https://wordpress.org/plugins/performance-tweaks/) - WordPress Performance Tweaks. Simple but effective.
* [Database Cleaner and Optimizer](https://wordpress.org/plugins/database-cleaner/) - Clean and optimize your database, for real! Lot of features, handle oversized databases, built on latest WP and PHP evolutions.
* [Meta Optimizer](https://wordpress.org/plugins/meta-optimizer/) - You can use Meta Optimizer to make your WordPress website load faster if you use meta information, for example Post/Comment/User/Term metas.

## Slow Query and Debugging Plugins
* [Query Monitor](https://wordpress.org/plugins/query-monitor/) - Query Monitor is a debugging plugin for anyone developing with WordPress.
* [Debug Bar](https://wordpress.org/plugins/debug-bar/) - Adds a debug menu to the admin bar that shows query, cache, and other helpful debugging information.
* [Query Monitor Add on plugins](https://github.com/johnbillion/query-monitor/wiki/Query-Monitor-Add-on-Plugins) - Third-party plugins that extend Query Monitor.
* [Fluent Query Logger](https://wordpress.org/plugins/fluent-query-logger/) - Query Logger Add-On for Query Monitor Plugin.

## NGNIX and Varnish Control Plugins
* [Ngnix Helper](https://wordpress.org/plugins/nginx-helper/) - Add greater control for purging NGNIX cache if using for page caching.
* [Varnish HTTP Purge](https://wordpress.org/plugins/varnish-http-purge/) - Varnish HTTP Purge sends a PURGE request to the URL of a page or post every time it it modified.
* [WP Super Cache nginx.conf example](https://github.com/vstoykovbg/nginx.conf-examples/blob/master/wp-super-cache-nginx.conf.md) - Example configuration for Nginx and WordPress with WP Super Cache plugin.
* [Rocket-Nginx](https://github.com/maximejobin/rocket-nginx) - Rocket-Nginx is a Nginx configuration for the WordPress cache plugin WP-Rocket.
* [WPBase Cache](https://wordpress.org/plugins/wpbase-cache/) - Plugin is developed to optimize wordpress deployment on varnish + nginx + php-fpm + php-apc server stack using three type of caches full page cache, db cache and opcode cache.
* [Nginx Cache](https://wordpress.org/plugins/nginx-cache/) - Purge the Nginx cache (FastCGI, Proxy, uWSGI) automatically when content changes or manually within WordPress.

## Caching Helping Plugins
* [WP Rocket Helpers](https://github.com/wp-media/wp-rocket-helpers) - This repository hosts a number of helper plugins that target some specific use cases for WP Rocket.
* [WP Rocket Footer JS](https://wordpress.org/plugins/rocket-footer-js/) - Unofficial WP-Rocket addon to force all JS both external and inline to the footer
* [WP Rocket ASYNC CSS](https://wordpress.org/plugins/rocket-async-css/) - This plugin will combine all inline and external CSS in the order found on the page and save it to WP-Rocket’s cache folder as a new file.
* [Inpsyde Menu Cache](https://github.com/inpsyde/menu-cache) - Easily cache rendered menus using the Transients API.
* [DB Cache Reloaded Fix](https://github.com/ivankristianto/DB-Cache-Reloaded-Fix) - The fastest cache engine for WordPress, that produces cache of database queries with easy configuration.
* [WP REST Cache](https://wordpress.org/plugins/wp-rest-cache/) - Adds caching to the WP REST API
* [Warm Cache](https://wordpress.org/plugins/warm-cache/) - Crawls your website-pages based on any XML sitemap. If you have a caching plugin this will keep your cache warm.
* [Inpsyde Translation Cache](https://github.com/inpsyde/translation-cache) - Improves site performance by caching translation files using WordPress object cache.
* [Cache Enabler rebuild cache Based on sitemap.xml](https://gist.github.com/iyaozhen/53e6a57a2f7e945ba1161953959a7cb2) - According to sitemap.xml rebuild cache in Cache Enabler.
* [Object Cache Flusher Button](https://github.com/georgestephanis/object-cache-flusher-button) - This plugin adds a button to the adminbar that simply flushes the object cache.
* [Cache Blocks](https://github.com/WordPressUtilities/wpucacheblocks) - Cache blocks.
* [Shin's Pageload Magic](https://wordpress.org/plugins/shins-pageload-magic/) - A lightweight Wordpress plugin that dramatically boosts your page's render speed.
* [Async JavaScript](https://wordpress.org/plugins/async-javascript/) - Async JavaScript adds a 'async' or 'defer' attribute to scripts loaded via wp_enqueue_script.
* [PageSpeed Purge Button](https://wordpress.org/plugins/wp-purge-pagespeed-button/) - One-click PageSpeed cache purging using an admin bar button.
* [Cache Version](https://github.com/kasparsd/cache-version) - Adds a version number (a timestamp) of all content that can be used in cache keys.
* [FacetWP Cache](https://facetwp.com/add-ons/caching/) - Caching support for FacetWP.
* [Far Future Expiry Header](https://wordpress.org/plugins/far-future-expiry-header/) - This plugin will add a "far future expiration" date for various file types to improve site performance.
* [WP Rocket User Role](https://gist.github.com/glueckpress/6a5ec40dc71e9775fcaa) - Restrict WP Rocket settings access to superadmins.
* [Hummingbird](https://wordpress.org/plugins/hummingbird-performance/) - Hummingbird zips through your site finding new ways to make it load faster, from file compression and minification to browser caching because when it comes to pagespeed, every millisecond counts.
* [Purge Varnish Cache](https://wordpress.org/plugins/purge-varnish/) - This plugin provides integration between your wordpress site and Varnish Cache to purge cache objects automate/manaully.
* [WP Critical CSS](https://wordpress.org/plugins/wp-criticalcss/) - Use CriticalCSS.com web service to automatically create the required CSS for above the fold.
* [Multisite Support for WP Rocket](https://wordpress.org/plugins/multisite-wp-rocket/) - Plugin to enable WP-Rocket to be managed in multisite.
* [FV Gravatar Cache](https://wordpress.org/plugins/fv-gravatar-cache/) - Speeds up your website by making sure the gravatars are stored on your website and not loading from the gravatar server.
* [ACF Simple Cache](https://wordpress.org/plugins/acf-simple-cache/) - Boost ACF speed by enabling json caching.
* [Widget Output Cache](https://wordpress.org/plugins/widget-output-cache/) - Caches widget output in WordPress object cache.
* [reBusted!](https://wordpress.org/plugins/rebusted/) - Force browsers to load the most recent file if modified.
* [WP Cache Remember](https://github.com/stevegrunwell/wp-cache-remember) - Helper for the WordPress object cache and transients.
* [Cache control by Cacholong](https://wordpress.org/plugins/cache-control-by-cacholong/) - Automates purging of Nginx Pagespeed cache and Nginx FastCGI cache on your Nginx server(s).
* [Cache-Control](https://wordpress.org/plugins/cache-control/) - Configurable HTTP Cache-Control headers for webpages generated by WordPress.
* [Better Resource Hints](https://wordpress.org/plugins/better-resource-hints/) - Easy preloading, prefetching, and HTTP/2 server pushing for your CSS and JavaScript.
* [Real IP and Geo for Cloudflare](https://wordpress.org/plugins/real-ip-and-geo-for-cloudflare/) - Saves and displays visitors' real IP and location, instead of Cloudflare's.
* [Autoclear Autoptimize Cache](https://wordpress.org/plugins/autoclear-autoptimize-cache/) - A companion plugin for Autoptimize that automatically clears cache if it grows larger then selected size.
* [WP Rocket LoadCSS](https://wordpress.org/plugins/enhance-wp-rocket-loadcss/) -  WordPress plugin to quickly modify php output with appropriate loadCSS syntax.
* [Quicklink for WordPress](https://wordpress.org/plugins/quicklink/) -  Faster subsequent page-loads by prefetching in-viewport links during idle time.
* [WP Admin Cache](https://wordpress.org/plugins/wp-admin-cache/) -  The first cache plugin for WordPress admin area.
* [Admin UI Cleaner](https://wordpress.org/plugins/admin-ui-cleaner/) -  Cleanup WordPress admin area.
* [Flying Pages](https://wordpress.org/plugins/flying-pages/) -  Load inner pages instantly, intelligently.
* [WP FOFT Loader](https://github.com/seezee/WP-FOFT-Loader) -  Implements and automates Zach Leatherman'sCritical FOFT with Data URI.
* [API Cache Pro](https://wordpress.org/plugins/api-cache-pro/) -  A simple plugin to cache WP Rest API Requests.
* [OPcache Manager](https://wordpress.org/plugins/opcache-manager/) -  OPcache statistics and management right in the WordPress admin dashboard.
* [Faster Woo Widgets](https://www.wpintense.com/product/faster-woo-widgets/) -  Gorgeous WooCommerce widgets built to be lightning fast, especially on large sites with hundreds of thousands (or millions) of products.
* [Static 404](https://wordpress.org/plugins/static-404/) -  Quickly output a 404 for static files that aren’t found, rather than loading the normal 404 page.
* [WP Meteor](https://wordpress.org/plugins/wp-meteor/) -  Improves your page speed, even on top of your existing optimizations.
* [Staatic](https://wordpress.org/plugins/staatic/) -  Staatic for WordPress allows you to generate a highly optimized static version of your WordPress site.
* [Core Web Vitals & PageSpeed Booster](https://wordpress.org/plugins/core-web-vitals-pagespeed-booster/) -  Do you want to speed up your WordPress site? Fast loading pages improve user experience, increase your pageviews, and help with your WordPress SEO.
* [The Cache Purger](https://wordpress.org/plugins/the-cache-purger/) -  Plugin attemps to clear all plugin based and server based caches.
* [HTTP2 push content](https://wordpress.org/plugins/http2-push-content/) -  Push all CSS and JS file throuhg http2 server, plugin add extra files that you want to push like images font files.
* [Encute](https://wordpress.org/plugins/encute/) -  Fluent management of scripts and styles.
* [Cache Purge Helper](https://wordpress.org/plugins/cache-purge-helper/) -  Adding additional hooks to trigger nginx-helper or lscache plugin purges.
* [GDPR Cache Scripts & Styles](https://wordpress.org/plugins/gdpr-cache-scripts-styles/) -  Caches external scripts and styles and serves them from your local website to make it more compliant with GDPR regulations.
* [Ajax loader + Cache](https://wordpress.org/plugins/ajax-loader-cache/) -  Ajax loading + built-in cache for WordPress, compatible with other cache plugins like WP-Rocket.
  
## WP-CLI Commands and Packages
* [WP Orphans](https://github.com/liquidweb/wp-orphans) - Locate and remove orphaned media from the WordPress media library.
* [wp transient](https://developer.wordpress.org/cli/commands/transient/) - Adds, gets, and deletes entries in the WordPress Transient Cache.
* [wp db optimize](https://developer.wordpress.org/cli/commands/db/optimize/) - Optimizes the database.
* [wp cache flush](https://developer.wordpress.org/cli/commands/cache/flush/) - Flushes the object cache.
* [wp media](https://developer.wordpress.org/cli/commands/media/) - Imports files as attachments, regenerates thumbnails, or lists registered image sizes.
* [wp media regenerate](https://developer.wordpress.org/cli/commands/media/regenerate/) - Regenerates thumbnails for one or more attachments.
* [EWWW IO via WP-CLI](https://docs.ewww.io/article/25-optimizing-with-wp-cli) - EWWW Image Optimizer features a WP-CLI extension that allows you to optimize your images "en masse". 
* [WP CLI interface for WP Rocket](https://github.com/wp-media/wp-rocket-cli) - This repository contains a WP-CLI command for the WP Rocket plugin. After installing this plugin, you will have access to a wp rocket command.

## Performance Benchmarking Sites
* [WebPageTest](https://www.webpagetest.org/) - Run a free website speed test from multiple locations around the globe using real browsers (IE and Chrome) and at real consumer connection speeds. You can run simple tests or perform advanced testing including multi-step transactions, video capture, content blocking and much more.
* [KeyCDN Site Speed Test](https://tools.keycdn.com/speed) - A page speed test that includes a waterfall breakdown and the website preview. Select any of the 14 test locations.
* [KeyCDN Performance Test](https://tools.keycdn.com/performance) - A free online web performance test. Query a single asset from 14 test locations.
* [Sucuri Load Time Tester](https://performance.sucuri.net/) - How fast is your site? You can test here the performance of any of your sites from across the globe.
* [GTmetrix](https://gtmetrix.com/) - Start optimizing your site! GTmetrix provides explanations for each recommendation, and gives you actionable advice.
* [Pingdom](https://tools.pingdom.com/) - Enter a URL to test the load time of that page, analyze it and find bottlenecks.
* [DebugBear Speed Test](https://www.debugbear.com/test/website-speed) - Test website speed and get performance recommendations.

## Load Impact Tools
* [Locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
* [Bees with Machine Guns!](https://github.com/newsapps/beeswithmachineguns) - A utility for arming (creating) many bees (micro EC2 instances) to attack (load test) targets (web applications).
* [Iago](https://github.com/twitter/iago/) - A load generator, built for engineers.
* [k6](https://github.com/loadimpact/k6) - A modern load testing tool, using Go and JavaScript.
* [k6 Cloud](https://k6.io/cloud/) - The k6 Cloud is a commercial SaaS product that we’ve designed to be the perfect companion to k6 OSS.
* [Apache JMeter](https://github.com/apache/jmeter) - Apache JMeter is a 100% pure Java application designed to test and measure performance. It may be used as a highly portable server benchmark as well as multi-client load generator.
* [Artillery](https://github.com/shoreditch-ops/artillery) - Artillery is a modern, powerful, easy-to-use load-testing toolkit. Artillery has a strong focus on developer happiness & ease of use, and a batteries-included philosophy.
* [Serverless Artillery](https://github.com/Nordstrom/serverless-artillery) - Combine serverless with artillery and you get serverless-artillery (a.k.a. serverless-artillery) for instant, cheap, and easy performance testing at scale.
* [Gatling](https://github.com/gatling/gatling) - Gatling is a stress tool. Development is currently focusing on HTTP support.
* [Seige](https://github.com/JoeDog/siege) - Siege is an open source regression test and benchmark utility. It can stress test a single URL with a user defined number of simulated users, or it can read many URLs into memory and stress them simultaneously.
* [Tsung](https://github.com/processone/tsung) - Tsung is multi-protocol distributed load testing tool.
* [Wrk](https://github.com/wg/wrk) - Wrk is a modern HTTP benchmarking tool capable of generating significant load when run on a single multi-core CPU. It combines a multithreaded design with scalable event notification systems such as epoll and kqueue.
* [Boom2](https://github.com/tarekziade/boom2) - Like Boom, but based on Molotov.
* [Vegeta](https://github.com/tsenart/vegeta) - Vegeta is a versatile HTTP load testing tool built out of a need to drill HTTP services with a constant request rate. It can be used both as a command line utility and a library.
* [Loader](https://loader.io/) - Loader.io is a FREE load testing service that allows you to stress test
your web-apps & apis with thousands of concurrent connections.

## New Relic Plugins
* [New Relic Reporting for WordPress](https://wordpress.org/plugins/wp-newrelic/) - New Relic APM reports for WordPress

## NGNIX Configs
* [Browser caching rules for NGNIX and expire headers](https://gist.github.com/matthewjackowski/062be03b41a68edbadfc) - Browser caching rules for NGNIX and expire headers being set.
* [Enabling Gzip compression in NGNIX](https://gist.github.com/lukecav/a8e63b732e2cfd0008c6f82d4a3191fe) - Enabling Gzip compression in NGNIX.
* [NGNIX Modules](https://github.com/nginx-modules) - Forked community NGNIX modules.
* [NGINX Amplify Agent](https://github.com/nginxinc/nginx-amplify-agent) - The NGINX Amplify Agent is a Python application that provides system and NGINX metric collection.
* [Nginx WordPress Configurations](https://github.com/davidegreenwald/Nginx-for-WordPress-Configurations) - TNginx-only, Apache-free configurations for WordPress with PHP-FPM, FastCGI cache, SSL, security settings, .webp support, and phpMyAdmin (just in case!). Mix and match the .conf files for your preferred configuration and traffic needs.

## Apache Configs
* [Browser caching rules, mod_deflate and expires](https://gist.github.com/lukecav/c806c253608a7b9abfcb572bf46eb54c) - Browser caching rules for Apache, mod_deflate and expire headers being set.
* [mod_expires example](https://gist.github.com/lukecav/a9fa14d32d08cca818b7a7762eef84aa) - mod_expires examples for most common file types.

## Varnish Configs
* [Varnish 4 VCL for WordPress](https://gist.github.com/lukecav/ed29bd779ccb2f8a46fc8b30ed48c141) - Varnish 4 VCL configuration for WordPress. Also allows purging.
* [Example VCL file for Varnish](https://github.com/nicolargo/varnish-nginx-wordpress/blob/master/varnish/varnish4-wordpress) - Update to work with Varnish 4.
* [Install + Configure Varnish 3 Cache with NGNIX for WooCommerce Speed](https://guides.wp-bullet.com/install-configure-varnish-3-cache-nginx-woocommerce-speed/) - Varnish is one of the best WooCommerce caching solutions I have tried. I’ve managed to get WooCommerce shop load times under 1 second.
* [Cache AJAX GET Requests in Varnish](https://gist.github.com/lukecav/2e5b24ffda25e897c5bc5f169349607b) - Possibility to cache admin-ajax GET requests.
* [Gzip in Varnish](https://gist.github.com/lukecav/bf4d647ab4b8bb309fd8f9f2948ed106) - Set to Gzip, deflate or remove entirely in Varnish.
* [How to check if chosen Varnish cache size is ideal](https://serverfault.com/questions/54276/how-to-check-if-chosen-varnish-cache-size-is-ideal) - You can monitor how much of the maximum cache size (512 MB in this case) that Varnish has allocated by running varnishstat. Then look for the output lines "bytes allocated" and "bytes free".

## Further Reading
* [WordPress Performance – Breaking It Down by HTTP Requests](https://www.keycdn.com/blog/wordpress-performance/) - WordPress can be a tricky beast as they say when it comes to web performance. Especially if you are comparing it against others running static sites.
* [Cloudflare Cache WordPress Posts and Pages Guide](https://guides.wp-bullet.com/cloudflare-cache-wordpress-posts-and-pages-guide/) - Cloudflare helps speed up WordPress and WooCommerce sites all around the world. Powered by more than 100 datacenters globally, Cloudflare’s CDN and security is a great addition to any web site.
* [18 Tips on How to Speed Up WordPress](https://www.keycdn.com/blog/speed-up-wordpress/) - WordPress is an amazing CMS platform, but it can also be quite slow if not optimized correctly. In this guide, we will show you how to speed up WordPress by sharing our web performance strategies and recommendations.
* [15 Website Speed Test Tools for Analyzing Web Performance](https://www.keycdn.com/blog/website-speed-test-tools/) - That is why it is important to take advantage of the many free website speed test tools available out there so you can achieve optimal performance.
* [Batch Optimize JPG Lossy Linux Command Line with jpeg-recompress](https://guides.wp-bullet.com/batch-optimize-jpg-lossy-linux-command-line-with-jpeg-recompress/) - Optimizing your images can feel like black magic sometimes. The safest JPG compression is lossless meaning no quality loss (guide), lossy compression has far superior space savings.
* [Cache AJAX GET Requests with Cloudflare and Varnish](https://guides.wp-bullet.com/cache-ajax-get-requests-with-cloudflare-and-varnish/) - AJAX requests are typically used to provide dynamic content on WordPress sites and bypass cache. I have already shown how to Cache AJAX requests with Varnish to bypass PHP and MySQL for AJAX processing by storing the cache in Varnish.
* [How to Diagnose High Admin-Ajax Usage on Your WordPress Site](https://kinsta.com/blog/admin-ajax/) - A very common scenario when dealing with WordPress is diagnosing high admin-ajax.php usage. If you have been working with WordPress for a while, you have most likely encountered this when running speed tests or checking your server access logs.
* [How to Enable GZIP Compression in WordPress](https://kinsta.com/knowledgebase/enable-gzip-compression/) - To achieve fast load times on your WordPress site, decreasing the size of your pages is crucial. This can mean the difference between a site that loads in under 1 second and one that feels like its crawling.
* [How to Fix “Specify a Vary: Accept-Encoding Header” Warning](https://kinsta.com/knowledgebase/specify-vary-accept-encoding-header/) - Are you seeing the “Specify a Vary: Accept-Encoding Header” warning in Pingdom, GTmetrix, or Google PageSpeed Insights on your WordPress site? This is an HTTP header and should be included on every origin server response, as it tells the browser whether or not the client can handle compressed versions of the content.
* [WordPress Cache Enabler Plugin](https://www.keycdn.com/support/wordpress-cache-enabler-plugin/) - The WordPress Cache Enabler plugin is a lightweight caching plugin that creates static HTML files and stores them on your web server. This means that a static HTML file will be delivered whenever possible to provide users with the response data that would otherwise involve the resource intensive process of using the WP core, plugins, and database.
* [Setting Up WooCommerce Cache](https://www.keycdn.com/support/setting-up-woocommerce-cache/) - WordPress caching plugins are a popular choice when looking for ways to improve page load times.
* [Configuring caching plugins Excluding pages from the cache for WC](https://docs.woocommerce.com/document/configuring-caching-plugins/) - If using caching plugins (such as WP Super Cache or W3 Total Cache), make sure you exclude the following pages from the cache through their respective settings panels.
* [A Guide on Web Font Optimization in WordPress](https://kinsta.com/blog/web-font-optimization/) - Web fonts are a staple of modern web design and used by the overwhelming majority of WordPress websites. Optimizing the use and delivery of web fonts is critical because poorly optimized web fonts can bog down the performance of your website.
* [Troubleshooting slow page speed on your WordPress site](https://torbjornzetterlund.com/troubleshooting-slow-page-speed-on-your-wordpress-site/) - If you think that your wordpress pages are loading slowly, it is time to do some troubleshooting to improve the page speed. Do not wait in doing the troubleshooting and let your site’s success be its downfall. 
* [What is hit-for-pass in Varnish](https://info.varnish-software.com/blog/hit-for-pass-varnish-cache) - There is a term in Varnish Cache that every Varnish Cache user should know: “Hit for pass”. Like other Varnish Cache terms it is not self-explanatory and in order to understand what it is you’ll need to understand some of the mechanics of the caching.
* [10 Varnish Cache mistakes and how to avoid them](https://info.varnish-software.com/blog/10-varnish-cache-mistakes-and-how-avoid-them) - Caching an object with a Set-Cookie header can have devastating effects, as any client requesting the object will get that same cookie set.
* [How do I enable HTTP/2 Server Push in WordPress](https://support.cloudflare.com/hc/en-us/articles/115002816808-How-do-I-enable-HTTP-2-Server-Push-in-WordPress) - HTTP/2 Server Push allows a website to push content to a browser, without having to wait for the HTML of one page to render first.
* [Get to know New Relic Reporting for WordPress](https://10up.com/blog/2017/new-relic-wordpress/) - New Relic is a SaaS product that offers application performance monitoring (APM), which provides developers with real-time data for use in proactive diagnostics as well as debugging. This data—including basic information about WordPress hooks, plugins, and themes—can be queried and visualized using the New Relic Insights dashboard.
* [What Is HTTP/3 – Lowdown on the Fast New UDP-Based Protocol](https://kinsta.com/blog/http3/) - HTTP/3 builds on User Datagram Protocol (UDP), and is already being used by prominent internet companies such as Google and Facebook.
* [Special infrastructure for web applications](https://github.com/szepeviktor/infrastructure-for-hosting-web-applications) - Build infrastructure for web applications following Viktor's policy on providing services.
* [AI-Powered WordPress](https://www.manning.com/books/ai-powered-wordpress) - A book that enables anyone to harness artificial intelligence to create impressive and professional-looking WordPress websites.

Hope this was helpful.

For any missing resources, please add them as issues. https://github.com/lukecav/awesome-wp-speed-up/issues
