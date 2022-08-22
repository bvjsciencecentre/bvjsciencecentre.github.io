# BVJ Science Centre

[Live Demo](https://github.com/udaycruise2903/bvjsc-website) 

## Installation

### Installing Ruby & Jekyll

If this is your first time using Jekyll, please follow the [Jekyll docs](https://jekyllrb.com/docs/installation/) and make sure your local environment (including Ruby) is setup correctly.

### Installing Theme

Download or clone the theme.

To run the theme locally, navigate to the theme directory and run:

```
bundle install
```

To start the Jekyll local development server.

```
bundle exec jekyll serve
```

Due to the usage of cloudinary, use this command to run local server

```
jekyll serve --config _config_dev.yml,_config.yml
```

To build the theme.

```
bundle exec jekyll build
```

### Github Pages

This theme has been tested to work with Github Pages (and Github Project Pages). When using Github Pages you will need to update the `baseurl` in the `_config.yml` otherwise all the css, images and paths will be broken.

For example the site https://bvjsciencecentre.github.io/bvjsci would have `baseurl: "/bvjsci/"`

Leave a star ⭐🙏🏻


