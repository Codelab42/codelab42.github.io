---
layout: post
title:  "Cache Warmer: the easiest way to warm your cache"
date:   2015-11-12 11:00:00
categories: cache-warmer
permalink: /blog/cache-warmer/cache-warming-keeps-your-site-fast
excerpt: So you have your caching mechanism on your website all set up and working. Great! Once the cache has been built, your pages will be delivered to your visitors as fast as possible. But have you also thought about warming your cache?
---

![Cache Warmer banner](/images/cache-warmer-banner.png)


*So you have your caching mechanism on your website all set up and working. Great! Once the cache has been built, your pages will be delivered to your visitors as fast as possible.*

## What is cache warming


Regardless of which caching system you use - the built-in caching system offered by your CMS or an external system such as Varnish - there is one thing that all caching systems have in common: **the cache needs to be build for each page before it can be used.** This cache building process happens when a page is viewed for the first time. This usually means that whoever visits a page first will experience a slow page and cause an increased load on your server.
If you want to keep your site fast for all of your visitors then you’ll need a way to make sure that your cache is **already built before your visitors arrive.** This process of building your cache in advance is called **cache warming.**

## How to warm your cache

Developers have lots of ways to handle cache warming: numerous scripts can be found online and some CMS systems even offer cache warmer modules. In the world of Drupal you can use a module such as [https://www.drupal.org/project/cache_warmer] or a script such as [http://dominiquedecooman.com/use-varnish-xmlsitemap-cron-and-bash-warm-cache-fast-pages]

These solutions will work well for many but what if you’re not an experienced developer? Or what if you don’t have the time to search for a script, test it and modify it to your needs? If you're looking for the easiest way to warm your cache then you’ll love our [Cache Warmer].

## Cache Warmer

Our [Cache Warmer] is designed to make your cache warming as painless as possible. We’ve made our cache warming tools available via an easy-to-use online interface so that you can start your first cache warming job in minutes. No coding required! Some of the features include:

- Manage cache warming for an unlimited amount of projects from within a single interface.
- Start your cache warm jobs immediately or schedule them.
- Let our built-in crawler determine which pages will be cache warmed or let it use your sitemap.xml. Enter a list of URLs for full control.
- Statistics are kept each time we warm your cache. We will let you know if we encounter any broken pages on your site so that you can take action immediately.

We’ve made the Cache Warmer very configurable so that you can use it for lots of different scenario’s. Some examples:

- You are launching a new site and want to make sure that all pages are cached before launch.
- You automatically publish articles at 3AM each night and want to make sure that they are cached.
- You clear your cache every night and want to make sure that the cache is rebuilt immediately afterwards.


If you are using Drupal as your CMS you can even use the Cache Warmer connect module to automatically build your cache after each cache clear.

Test the Cache Warmer for free at [cache-warmer.com] and keep your site fast all of the time!

[http://dominiquedecooman.com/use-varnish-xmlsitemap-cron-and-bash-warm-cache-fast-pages]: http://dominiquedecooman.com/use-varnish-xmlsitemap-cron-and-bash-warm-cache-fast-pages
[https://www.drupal.org/project/cache_warmer]: https://www.drupal.org/project/cache_warmer
[Cache Warmer]:   http://www.cache-warmer.com
[cache-warmer.com]:   http://www.cache-warmer.com
[Cache Warmer connect module]: https://www.drupal.org/project/cachewarmer_connect
