# Jekyll REST API

This is a read only JSON API, making it easier to connect third party systems
to your content, or do more advanced renderings with javascript on your jekyll site
that can't be done with the liquid syntax.

### Examples of what you can build with this API:
- Search trough *all* your Jekyll posts with javascript, without having to
    parse the HTML.
- Define settings for your javascript via your _config.yml
- Create a javascript code that will alert the user on the screen when
    there is a new post available
- Apply filters to the post content before rendering, such as wrapping all
    images in a different code for a lightbox system.

# Installation

#### Via git submodule

###### Installing
```bash
git submodule add 'https://github.com/riichard/jekyll-rest-api'
```

###### Using
```bash
curl http://myjekyllsite.com/jekyll-rest-api/posts.json
```
This also works like a charm on `.github.io` URLs. 

# Output examples

All output examples can also be found in the `output-example` folder.

### /posts.json
```json

```

### /settings.json
```json

```



