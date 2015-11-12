---
layout: post
title:  "Cache Warming keeps your site fast"
date:   2015-11-12 11:00:00
categories: cache-warmer
permalink: /blog/cache-warmer/cache-warming-keeps-your-site-fast
---

![Cache Warmer banner](/images/cache-warmer-banner.png)


So you have your caching mechanism on your website all set up and working. Great! Once the cache has been built, your pages will be delivered to your visitors as fast as possible.

Regardless of which caching system you use - the standard caching mechanism that comes with your Wordpress or Drupal or more advanced systems such as Varnish - you still need that first visitor on each page to build your cache. That first visitor will experience painfully slow page-load times. The solution is cache warming: making sure that your cache has been built **before** a visitor opens up the page.

As a developer you have lots of ways to approach cache warming: there are numerous scripts available online and some website platforms even offer cache warmer modules. In the Drupal world you can use a module such as [cache_warmer] or if you prefer a script then [this blog post] will get you on your way.

These solutions will work well for a lot of people but what if you are not an experienced developer? Or if you simply don’t have the time to search for a script, test it, get it up and running and modify it to your needs? If you're looking for an easier solution then you should try the cache warming service at [cache-warmer.com].

The service of [cache-warmer.com] is designed to make cache warming as painless as possible. By offering it as a SAAS you can start your first cache warming job within minutes. Use our configurable crawler, your sitemap.xml or upload a file with URLs for full control over which pages will be cache warmed. Then, start your cache warm job immediately or schedule it to happen when you want it. Thanks to these configuration options, you have full control over which pages will be cache warmed and when.

This makes it possible to use the service for different scenario’s. For example:

1. You are launching a new site and want to make sure that all pages are cached before launch.
2. You automatically publish articles at 3AM each night and want to make sure that they are cached.
3. You clear your cache every night and want to make sure that the cache is rebuilt immediately afterwards.

Statistics are kept after each cache warming job so that you can see how many pages were processed. We will also alert you when we encounter issues with the pages on your site so that you can immediately take action.

If you are using Drupal as your CMS you can even use the cache-warmer connect module to automatically build your cache after each cache clear.

Test the cache warmer for free at [cache-warmer.com] and keep your site fast all of the time!

[this blog post]: http://dominiquedecooman.com/use-varnish-xmlsitemap-cron-and-bash-warm-cache-fast-pages
[cache_warmer]: https://www.drupal.org/project/cache_warmer
[cache-warmer.com]:   http://www.cache-warmer.com
