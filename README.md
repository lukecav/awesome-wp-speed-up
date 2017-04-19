# awesome-wp-speed-up
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
* [Performance Benchmarking Sites](#performance-benchmarking-sites)
* [Further Reading](#further-reading)

## Page Caching Plugins
* [WP Fastest Cache](https://wordpress.org/plugins/wp-fastest-cache/) - This plugin creates static html files from your dynamic WordPress blog.
* [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/) - This plugin generates static html files from your dynamic WordPress blog. After a html file is generated your webserver will serve that file instead of processing the comparatively heavier and more expensive WordPress PHP scripts.
* [Comet Cache](https://wordpress.org/plugins/comet-cache/) - If you care about the speed of your site, Comet Cache is one of those plugins that you absolutely MUST have installed Comet Cache takes a real-time snapshot (building a cache) of every Page, Post, Category, Link, etc. 
* [Cache Enabler](https://wordpress.org/plugins/cache-enabler/) - The Cache Enabler plugin creates static HTML files and stores them on the servers disk.
* [Simple Cache](https://wordpress.org/plugins/simple-cache/) - Simple Cache was constructed after getting frustrated with the major caching plugins available and building sites with developer-only complex caching solutions that get millions of page views per day.
* [Gator Cache](https://wordpress.org/plugins/gator-cache/) - Gator Cache is an easy to manage page cache for WordPress. Once installed, it automatically updates new and updated content in your cache.
* [Vendi Cache](https://wordpress.org/plugins/vendi-cache/) - Vendi Cache takes your slow database-driven pages and turns them into very fast static HTML files.
* [SG Optimizer](https://wordpress.org/plugins/sg-cachepress/) - This plugin is designed to link WordPress with the SiteGround Performance services.
* [Vendi Cache](https://wordpress.org/plugins/vendi-cache/) - Vendi Cache takes your slow database-driven pages and turns them into very fast static HTML files.
* [WP Rocket](https://wp-rocket.me/) - Your website at lightspeed.
* [W3 Total Cache Fixed](https://github.com/szepeviktor/w3-total-cache-fixed) - A community driven build of W3 Total Cache. The aim is to continuously incorporate fixes, improvements, and enhancements over the official WordPress release of W3 Total Cache.
* [WP-FFPC](https://wordpress.org/plugins/wp-ffpc/) - WP-FFPC is a cache plugin for WordPress.
* [Cachify](https://wordpress.org/plugins/cachify/) - Cachify optimizes your page loads by caching posts, pages and custom post types as static content.
* [Batcache](https://wordpress.org/plugins/batcache/) - Batcache uses Memcached to store and serve rendered pages.
* [Hyper Cache](https://wordpress.org/plugins/hyper-cache/) - Hyper Cache is a cache plugin specifically written to get the maximum speed for your WordPress site.
* [Powered Cache](https://wordpress.org/plugins/powered-cache/) - Comprehensive caching and performance plugin for WordPress.
* [WP Spider Cache](https://github.com/stuttter/wp-spider-cache) - WP Spider Cache is your friendly neighborhood caching solution for WordPress. It uses Memcached to store both objects & page output.
* [Redis Page Cache for WordPress](https://github.com/pressjitsu/pj-page-cache-red) - A Redis-backed full page caching plugin for WordPress, extremely flexible and fast. Requires a running Redis server and the PHP Redis PECL extension.
* [Varnish Caching](https://github.com/razvanstanga/varnish-caching-wordpress-plugin) - Complete Wordpress Varnish Cache 3.x/4.x integration.
* [WordPress Cache and CDN](https://wordpress.org/plugins/cache-performance/) - Fast, easy to use cache for WordPress with option for up-to 3 separate CDN’s – for js, css & images from 3 providers.

## Object Caching Plugins
* [WP Redis](https://wordpress.org/plugins/wp-redis/) - For sites concerned with high traffic, speed for logged-in users, or dynamic pageloads, a high-speed and persistent object cache is a must.
* [Redis Object Cache](https://wordpress.org/plugins/redis-cache/) - A persistent object cache backend powered by Redis. Supports Predis, PhpRedis (PECL), HHVM, replication, clustering and WP-CLI. 
* [Memcached Redux](https://wordpress.org/plugins/memcached-redux/) - Changes the famous Memcached WP Object Cache backend to actually use the Memcached class (not the Memcache class).
* [Fork of Memcached Redux](https://github.com/Ipstenu/memcached-redux) - The real Memcached (not Memcache) backend for the WP Object Cache.
* [Memcached](https://github.com/humanmade/memcache-object-cache) - Memcached backend for the WP Object Cache.
* [Memcached Is Your Friend Updated](https://github.com/wpbullet/memcached-is-your-friend) - Memcached via PHP Memcache or Memcached Class Support for WordPress with fixes for compatibility.
* [APCu Object Cache Backend](https://wordpress.org/plugins/apcu/) - Using this Plugin WordPress is able to store certain regular used elements into a persistent cache.

## Fragment Caching Plugins
* [Fragment Cache](https://github.com/Rarst/fragment-cache) - Fragment Cache is a WordPress plugin for partial and async caching of heavy front-end elements. It currently supports caching navigation menus, widgets, and galleries.
* [Blunt Cache](https://wordpress.org/plugins/blunt-cache/) - Blunt Cache is a persistent fragment and object cache for those of us that cannot use full page caching.

## Browser Caching Plugins
* [Speed Up – Browser Caching](https://wordpress.org/plugins/speed-up-browser-caching/) - This small plugin (10 Kb) enables browser caching in your Apache web server and help browser to cache a local copy of static files and improve page load times. 
* [WP Performance Score Booster](https://wordpress.org/plugins/wp-performance-score-booster/) - This plugin speed-up page load times and improve website scores in services like PageSpeed, YSlow, Pingdom and GTmetrix.

## Minification Plugins
* [Autoptimize](https://wordpress.org/plugins/autoptimize/) - Autoptimize makes optimizing your site really easy. It concatenates all scripts and styles, minifies and compresses them, adds expires headers, caches them, and moves styles to the page head and can move scripts to the footer.
* [WP Roids](https://wordpress.org/plugins/wp-roids/) - Fast AF caching! Plus minifies your site’s HTML, CSS & Javascript.
* [Minit](https://github.com/kasparsd/minit/) - Combine CSS files and Javascript files into single file in the correct order. Use the latest modified time in filename generation to ensure freshness. Load all external Javascript files asynchronously.
* [Minit Pro](https://github.com/markoheijnen/Minit-Pro) - Add additional functionality to the Minit plugin of Kaspars Dambis.

## CDN Integration Plugins
* [CDN Enabler](https://wordpress.org/plugins/cdn-enabler/) - A content delivery network (CDN) is a network of distributed edge servers, which accelerate your content around the globe. The main benefits of a CDN are scalability, reliability and performance.
* [Cloudflare](https://wordpress.org/plugins/cloudflare/) - The easiest way to setup Cloudflare for your WordPress site.
* [Fastly](https://wordpress.org/plugins/fastly/) - Using this plugin means you won’t have to purge content in Fastly when you make changes to your WordPress content. Purges will automatically happen with no need for manual intervention.
* [Purgely](https://github.com/CondeNast/purgely) - Purgely manages caching and purging behavior for WordPress sites using the Fastly edge caching services. The plugin sets up default behaviors based on best practices for WordPress websites.
* [DreamSpeed CDN](https://wordpress.org/plugins/dreamspeed-cdn/) - This plugin will automatically copy images, videos, documents, and any other media added through WordPress’ media uploader to DreamSpeed.
* [Full Site Cache for KeyCDN](https://wordpress.org/plugins/full-site-cache-kc/) - This plugin can help you to use KeyCDN on your WordPress, not only your Media and CSS, but also all HTML page.
* [Full Site Cache for CloudFront](https://wordpress.org/plugins/full-site-cache-cf/) - If you blog are using CloudFront on the main WordPress domain and you want to cache HTML page for not logged in user.
* [Cloudinary](https://wordpress.org/plugins/cloudinary-image-management-and-manipulation-in-the-cloud-cdn/) - With Cloudinary, all your images are automatically uploaded, normalized, optimized and backed-up in the cloud instead of being hosted on your servers.
* [Photon](https://jetpack.com/support/photon/) - Photon is an image acceleration and editing service for sites hosted on WordPress.com or on Jetpack-connected WordPress sites. That means less load on your host and faster images for your readers.
* [ILAB Media Tools](https://en-ca.wordpress.org/plugins/ilab-media-tools/) - ILAB Media Tools are a suite of tools designed to enhance media handling in WordPress in a number of ways.
* [WP Offload S3](https://deliciousbrains.com/wp-offload-s3/) - ILAB Media Tools are a suite of tools designed to enhance media handling in WordPress in a number of ways.
* [DADI CDN](https://github.com/dadi/cdn)A self-hosted, just-in-time asset manipulation and delivery application, providing a complete content distribution/delivery solution.

## Image Optimization Plugins
* [EWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/) - The EWWW Image Optimizer is a WordPress plugin that will automatically optimize your images as you upload them to your blog.
* [EWWW Image Optimizer Cloud](https://wordpress.org/plugins/ewww-image-optimizer-cloud/) - The EWWW Image Optimizer is a WordPress plugin that will automatically optimize your images as you upload them to your blog.
* [TinyPNG](https://wordpress.org/plugins/tiny-compress-images/) - Make your website faster by optimizing your JPEG and PNG images. This plugin automatically optimizes all your images by integrating with the popular image compression services TinyJPG and TinyPNG.
* [Imagify](https://wordpress.org/plugins/imagify/) - Speed up your website with lighter images without losing quality.
* [ImageRecycle](https://wordpress.org/plugins/imagerecycle-pdf-image-compression/) - ImageRecycle is an automatic Image and PDF content optimizer for WordPress website.
* [ShortPixel Image Optimizer](https://wordpress.org/plugins/shortpixel-image-optimiser/) - Increase your website’s SEO ranking, number of visitors and ultimately your sales by optimizing any image or PDF document on your website.
* [Kraken.io](https://wordpress.org/plugins/kraken-image-optimizer/) - This plugin allows you to optimize and resize new and existing WordPress image uploads through Kraken.io Image Optimizer’s API.
* [Optimus](https://wordpress.org/plugins/optimus/) - Optimus reduces the file size of uploaded media files automatically. Depending on the image and format, reductions in size of up to 70% are possible.
* [WP ImageEngine Responsive Image Resizer](https://wordpress.org/plugins/wp-imageengine/) - WP ImageEngine is an intelligent image CDN for optimizing, compressing and resizing images.
* [Image Compression and optimization](https://wordpress.org/plugins/wp-image-compression/) - Optimize your Images as well as Image Compression of upto 80%. Also resize images on upload to help reduce storage and bandwidth before compressing.
* [Media Cleaner](https://wordpress.org/plugins/media-cleaner/) - Clean your Media Library from the media which aren’t used in any of your posts, gallery and so on.

## Lazy Loading Plugins
* [Rocket Lazy Load](https://wordpress.org/plugins/rocket-lazy-load/) - Lazy Load displays images on a page only when they are visible to the user. This reduces the number of HTTP requests mechanism and improves the loading time.
* [Lazy Load](https://wordpress.org/plugins/lazy-load/) - Lazy Load displays images on a page only when they are visible to the user. This reduces the number of HTTP requests mechanism and improves the loading time.
* [Lazy Load XT](https://wordpress.org/plugins/lazy-load-xt/) - Lazy load images, YouTube and Vimeo videos, and iframes using Lazy Load XT.
* [Progressive Lazy Load](https://gist.github.com/Stegosource/3be8d6bdc168a957eabffdb0e1421850) - An example of my "Progressive Lazy Load" technique in WordPress using vanilla Javascript.
* [Lazy Load for Videos](https://wordpress.org/plugins/lazy-load-for-videos/) - This plugin improves page load times and increases your Google PageSpeed Score. It replaces embedded Youtube and Vimeo videos with a clickable preview image.
* [Disqus Conditional](https://wordpress.org/plugins/disqus-conditional-load/) - DCL is an advanced version of Disqus Commenting System, with which experience the boosted page loading speed difference. 
* [Lazy Facebook Comments](https://wordpress.org/plugins/lazy-facebook-comments/) - Use Facebook comments system in your website without slowing down your website. 
* [Lazy Load for Comments](https://wordpress.org/plugins/lazy-load-for-comments/) - Lazy load WordPress default commenting system without any complex configurations.
* [Velocity](https://wordpress.org/plugins/velocity/) - Velocity is a WordPress plugin for lazy loading video and audio embedded media – it’s an alternative loading method to the standard YouTube, Vimeo and SoundCloud iframe embeds.

## Reduce HTTP Requests on Load Plugins
* [Heartbeat Control](https://wordpress.org/plugins/heartbeat-control/) - Allows you to easily manage the frequency of the WordPress heartbeat API with just a few dropdowns.
* [Disable Emoji](https://wordpress.org/plugins/disable-emojis/) - This plugin disables the new WordPress emoji functionality.
* [Emoji Settings](https://wordpress.org/plugins/emoji-settings/) - Emoji Settings adds an option within your Writing Settings page to disable or enable emojis.
* [Compressed Emoji](https://wordpress.org/plugins/compressed-emoji/) - WordPress emoji comes from s.w.org and they are not optimized well, Compressed Emoji fixes this problem.
* [Disable Embeds](https://wordpress.org/plugins/disable-embeds/) - Disable Embeds
* [Disable Custom CSS](https://wordpress.org/plugins/disable-custom-css/) - This plugin automatically disables frontend database query for Custom CSS and Customizer section for setting Custom CSS, without need to manually choose any setting or option.
* [Plugin Organizer](https://wordpress.org/plugins/plugin-organizer/) - This plugin allows you to do the following, change the order that your plugins are loaded,selectively disable plugins by any post type or wordpress managed URL and adds grouping to the plugin admin age.
* [Query Strings Remover](https://wordpress.org/plugins/query-strings-remover/) - Query Strings Remover removes query strings from your static resources like CSS and JavaScript files.
* [WP Asset CleanUp](https://wordpress.org/plugins/wp-asset-clean-up/) - There are often times when you are using a theme and a number of plugins which are enabled and run on the same page.
* [WP Disable](https://wordpress.org/plugins/wp-disable/) - Reduce HTTP requests - Disable Emojis, Disable Gravatars, Disable Embeds and Remove Querystrings. Added support to disable pingbacks, disable trackbacks, close comments after 28 days, Added the ability to force pagingation after 20 posts, Disable WooCommerce scripts and CSS on non WooCommerce Pages, Disable RSS, Disable XML-RPC, Disable Autosave, Remove Windows Live Writer tag, Remove Shortlink Tag, Remove WP API from header.
* [Only Load Scripts and Styles if a shortcode is present](https://gist.github.com/Stegosource/8504035f7ff9417284a26af7e3c3db74) - Only load scripts and styles if a specific shortcode is present in the content when the page/post is saved.
* [Complete Analytics Optimization Suite (CAOS)](https://wordpress.org/plugins/host-analyticsjs-local/) - Only load scripts and styles if a specific shortcode is present in the content when the page/post is saved.
* [Gonzales](https://wordpress.org/plugins/wptimize/) - This plugin allows you to get rid of CSS and JavaScript files that are simply useless. Less is better, right? One of the biggest problem of modern websites is page weight.
* [WPtimize](https://tomasz-dobrzynski.com/wordpress-gonzales) - WPtimize is optimization and cleanup plugin for WordPress that cleanup all the unnecessary tags and scripts from your WordPress header and optimize your code for faster loading page speed, security and performance.
* [WP Load List](https://wordpress.org/plugins/wp-load-list/) - When you are trying to speed up your site, minifying CSS and JS files can really gain you some speed but can also break your site. This plugin allows you to get a full list of all CSS and JS files loading on each page so you can use this list to target the files you must avoid minifying.

## Database Optimization Plugins
* [WP-Optimize](https://wordpress.org/plugins/wp-optimize/) - WP-Optimize is an effective tool for automatically cleaning your WordPress database so that it runs at maximum efficiency.
* [WP-Sweep](https://wordpress.org/plugins/wp-sweep/) - WP-Sweep allows you to clean up unused, orphaned and duplicated data in your WordPress. It also optimizes your database tables.
* [Optimize Database after Deleting Revisions](https://wordpress.org/plugins/rvg-optimize-database/) - Host your Google Analytics javascript-file (analytics.js) locally and keep it updated using wp_cron().
* [Delete Expired Transients](https://wordpress.org/plugins/delete-expired-transients/) - Delete old, expired transients from the WordPress options table (wp_options), to prevent them from bloating your database and even slowing down your website.
* [Plugins Garbage Collector](https://wordpress.org/plugins/plugins-garbage-collector/) - Plugins Garbage Collector scans your WordPress database and shows the tables beyond of core WordPress installation.

## Slow Query and Debugging Plugins
* [Query Monitor](https://wordpress.org/plugins/query-monitor/) - Query Monitor is a debugging plugin for anyone developing with WordPress.
* [Debug Bar](https://wordpress.org/plugins/debug-bar/) - Adds a debug menu to the admin bar that shows query, cache, and other helpful debugging information.

## NGNIX and Varnish Control Plugins
* [Ngnix Helper](https://wordpress.org/plugins/nginx-helper/) - Add greater control for purging NGNIX cache if using for page caching.
* [Varnish HTTP Purge](https://wordpress.org/plugins/varnish-http-purge/) - Varnish HTTP Purge sends a PURGE request to the URL of a page or post every time it it modified.
* [WP Super Cache nginx.conf example](https://github.com/vstoykovbg/nginx.conf-examples/blob/master/wp-super-cache-nginx.conf.md) - Example configuration for Nginx and WordPress with WP Super Cache plugin.
* [Rocket-Nginx](https://github.com/maximejobin/rocket-nginx) - Rocket-Nginx is a Nginx configuration for the WordPress cache plugin WP-Rocket.
* [WPBase Cache](https://wordpress.org/plugins/wpbase-cache/) - Plugin is developed to optimize wordpress deployment on varnish + nginx + php-fpm + php-apc server stack using three type of caches full page cache, db cache and opcode cache.

## Caching Helping Plugins
* [WP Rocket Helpers](https://github.com/wp-media/wp-rocket-helpers) - This repository hosts a number of helper plugins that target some specific use cases for WP Rocket.
* [WP Rocket Static Resources List](https://github.com/wp-media/wp-rocket-static-resources-list) - List the CSS and JS files loaded on a WordPress page.
* [WP-Rocket Background Cache](https://wordpress.org/plugins/rocket-background-cache/) - This plugin will defer all cache pre-loading to wp-cron. If a page request comes and a page is not cached yet, wp-rocket will be disabled.
* [WP Rocket Footer JS](https://wordpress.org/plugins/rocket-footer-js/) - Unofficial WP-Rocket addon to force all JS both external and inline to the footer
* [WP Rocket ASYNC CSS](https://wordpress.org/plugins/rocket-async-css/) - This plugin will combine all inline and external CSS in the order found on the page and save it to WP-Rocket’s cache folder as a new file.
* [VIP Performance Plugin](https://github.com/Automattic/vip-code-performance) - A plugin that helps every site benefit from the performance features built into WordPress.com VIP.
* [Inpsyde Menu Cache](https://github.com/inpsyde/menu-cache) - Easily cache rendered menus using the Transients API.
* [WP Static HTML Output](https://wordpress.org/plugins/static-html-output-plugin/) - This plugin produces a static HTML version of your wordpress install, incredibly useful for anyone who would like the publishing power of wordpress but whose webhost doesn’t allow dynamic PHP driven sites.
* [DB Cache Reloaded Fix](https://github.com/ivankristianto/DB-Cache-Reloaded-Fix) - The fastest cache engine for WordPress, that produces cache of database queries with easy configuration.
* [OPcache Dashboard](https://wordpress.org/plugins/opcache/) - As you know, OPcache has no management page. This plugin offers you the OPcache dashboard designed for WordPress.
* [WP REST API Cache](https://wordpress.org/plugins/wp-rest-api-cache/) - Enable caching for WordPress REST API and increase speed of your application.
* [Warm Cache](https://wordpress.org/plugins/warm-cache/) - Crawls your website-pages based on any XML sitemap. If you have a caching plugin this will keep your cache warm.
* [Cache Buddy](https://github.com/markjaquith/cache-buddy) - Minimizes the situations in which logged-in users appear logged-in to WordPress, which increases the cacheability of your site.
* [Inpsyde Translation Cache](https://github.com/inpsyde/translation-cache) - Improves site performance by caching translation files using WordPress object cache.
* [Batcache Manager](https://github.com/spacedmonkey/batcache-manager) - Batcache manager is a drop-in solution, that adds cache clearing the popular caching Batcache plugin by Automattic. This plugin is based on the work by Andy Skelton and expands upon it, clearing archive pages, author pages and feeds.
* [Advanced Nav Cache](https://github.com/spacedmonkey/advanced-nav-cache) - Cache wp_nav_menu output in object cache.
* [Advanced Comment Cache](https://github.com/spacedmonkey/advanced-comment-cache) - A plugin to force caching of comments in wp_comment_query.
* [Clear cache for Timber](https://github.com/ogrosko/clear-cache-for-timber) - Clear cache for Timber and Twig caching.
* [Cache Enabler rebuild cache Based on sitemap.xml](https://gist.github.com/iyaozhen/53e6a57a2f7e945ba1161953959a7cb2) - According to sitemap.xml rebuild cache in Cache Enabler.
* [Object Cache Flusher Button](https://github.com/georgestephanis/object-cache-flusher-button) - This plugin adds a button to the adminbar that simply flushes the object cache.
* [Analytics For Cloudflare](https://github.com/ChuckMac/analytics-for-cloudflare) - This is a WordPress plugin to connect your WordPress dashboard to your CloudFlare account to display some key analytics data.

## Performance Benchmarking Sites
* [WebPageTest](https://www.webpagetest.org/) - Run a free website speed test from multiple locations around the globe using real browsers (IE and Chrome) and at real consumer connection speeds. You can run simple tests or perform advanced testing including multi-step transactions, video capture, content blocking and much more.
* [KeyCDN Site Speed Test](https://tools.keycdn.com/speed) - A page speed test that includes a waterfall breakdown and the website preview. Select any of the 14 test locations.
* [KeyCDN Performance Test](https://tools.keycdn.com/performance) - A free online web performance test. Query a single asset from 14 test locations.
* [Sucuri Load Time Tester](https://performance.sucuri.net/) - How fast is your site? You can test here the performance of any of your sites from across the globe.
* [GTmetrix](https://gtmetrix.com/) - Start optimizing your site! GTmetrix provides explanations for each recommendation, and gives you actionable advice.
* [Pingdom](https://tools.pingdom.com/) - Enter a URL to test the load time of that page, analyze it and find bottlenecks.

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

Hope this was helpful.

For any missing resources, please add them as issues. https://github.com/lukecav/awesome-wp-speed-up/issues
