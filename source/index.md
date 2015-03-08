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
<?php
$json = file_get_contents('http://vel.myjoomla.io/');
```

```shell
curl "http://vel.myjoomla.com"
```

> In the json is a data array that contains json objects like this

```json
{ 
"last_updated": 
{
  "timestamp": "1425675184",
  "human": "Friday 6th March 2015"
},
data: [
{
  "official_vel_link": "http://vel.joomla.org/live-vel/1493",
  "title": "myJoomla extension",
  "type": "RFI",
  "published_date": "22/09/2014",
  "component_name": "Joomla extension Gallery",
  "com_whatever": "com_example",
  "version_effected": "1.5",
  "version_effected_trend": "<",
  "developer_website": "https://www.example.com",
  "extension_webpage": "https://www.example.com/joomla-photo-example",
  "developers_email": "assist@example.com",
  "response_url": ""
}
]
}
```

The Joomla Vulnerable Extension List, is a public list published by Joomla.org or reported plugins, extensions, modules or templates from 3rd party developers that have known or resolved security issues with them.

At the time of writing there is no practical way of querying this data as its published in such a bad state (individual Joomla content items) on the official site.

myJoomla.io providers the _only_ public json interface that is updated and maintained of this data. 

`License: GPL`

<aside class="notice">
This JSON is provided for free, don't abuse this by hammering it with massive of calls please. Be nice. Cache.
</aside>

