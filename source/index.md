---
title: myJoomla.io API Reference

language_tabs:
  - shell
  - php
  

toc_footers:
  - <a href='http://myjoomla.com'>Check our manage.myjoomla.com</a>

search: true
---

# Introduction

Welcome to the myJoomla.io API Reference

This document will document all API's published by Phil Taylor as part of the myJoomla.com service, along with free API's available to all based on Joomla based data.

Any questions please email Phil direct at phil@phil-taylor.com

# Vulnerable Extensions List

> This is a public static json file


```php
$json = file_get_contents('http://vel.myjoomla.io/');
```

```shell
curl "http://vel.myjoomla.com"
```

> In the json is a data array that contains json objects like this

```json
{
  "official_vel_link": "http://vel.joomla.org/live-vel/1493-joomla-mac-gallery-1-5-and-below",
  "title": "Joomla Mac Gallery 1.5 and below",
  "type": "RFI",
  "published_date": "22/09/2014",
  "component_name": "Joomla Mac Gallery",
  "com_whatever": "com_macgallery",
  "version_effected": "1.5",
  "version_effected_trend": "<",
  "developer_website": "https://www.apptha.com",
  "extension_webpage": "https://www.apptha.com/category/extension/joomla/joomla-photo-gallery",
  "developers_email": "assist@apptha.com",
  "response_url": ""
}
```

The Joomla Vulnerable Extension List, is a public list published by Joomla.org or reported plugins, extensions, modules or templates from 3rd party developers that have known or resolved security issues with them.

At the time of writing there is no practical way of querying this data as its published in such a bad state (individual Joomla content items) on the official site.

myJoomla.io providers the _only_ public json interface that is updated and maintained of this data. 

`License: GPL`

<aside class="notice">
This JSON is provided for free, dont abuse this by hammering it with massive of calls please. The official VEL list rarely changes. Be nice.
</aside>

