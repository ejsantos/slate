---
title: Stellar Loyalty Home

language_tabs:
  - ruby
  - shell

includes:
  - how_tos
  - concepts
  - errors

search: true
---

# Stellar Docs

Picnic is a documentation template for Jekyll that came to life out of the need of having a simple and elegant way to write, view, and search documentation for projects of all sizes.

Picnic is heavily inspired by existing projects such as [Slate](https://github.com/tripit/slate), [Daux.io](https://github.com/justinwalsh/daux.io), and [Docco](https://github.com/jashkenas/docco). However, unlike these projects, Picnic is fully compatible with Jekyll-based GitHub Pages and can therefore be hosted without needing to be built beforehand.

Perhaps best of all, Picnic features full-text search using [lunr.js](http://lunrjs.com/). The search data is asynchronously streamed and indexed in chunks using [Oboe.js](http://oboejs.com/), so even if you have hundreds of pages it won't slow down your docs.

# Authentication

This is an example for using the right side thingy

> To authorize, use this code:

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

## Authentication level 2

This is an authentication level 2

### Authentication level 3

Pretty deep authentication!
