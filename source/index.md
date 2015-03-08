---
title: myJoomla.io API Reference

language_tabs:
  - curl
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

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```curl
curl "http://vel.myjoomla.com"
```

> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace `meowmeowmeow` with your personal API key.
</aside>

