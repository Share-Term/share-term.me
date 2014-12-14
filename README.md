Starter Bloggify Site
=====================
A starter Bloggify website.

## Installation

```sh
$ git clone --recursive git@github.com:Bloggify/Starter.git content
```

## Configuration

```json
{
  "site": {
    "title": "Test Bloggify",
    "description": "Another beautiful Bloggify website"
  },
  "blog": {
    "path": "/blog",
    "slug": "blog",
    "order": "3",
    "articles": {
      "limit": "3"
    }
  },
  "options": {
      "customCSS": ["/custom/css.css"]
  },
  "plugins": [
    {
      "name": "article-tags",
      "source": "git@github.com:BloggifyPlugins/article-tags.git",
      "version": "2.0.0"
    },
    {
      "name": "_custom-client-files",
      "source": "git@github.com:BloggifyPlugins/custom-client-files.git",
      "version": "2.0.0"
    },
    {
      "name": "_api",
      "source": "git@github.com:IonicaBizau/api.git",
      "version": "1.0.0"
    },
    {
      "name": "_dashboard",
      "source": "git@github.com:IonicaBizau/dashboard.git",
      "version": "1.0.0",
      "config": {
        "users": [
          {
            "username": "admin",
            "displayName": "Admin",
            "password": "admin"
          }
        ]
      }
    },
    {
      "name": "lightbox",
      "source": "git@github.com:BloggifyPlugins/lightbox.git",
      "version": "2.0.0"
    }
  ]
}
```
