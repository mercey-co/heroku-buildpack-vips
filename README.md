heroku-buildpack-vips
=====================

## About this buildpack

This buildpack contains the results of a Meson build of libvips in a
container created from the `heroku/heroku:24-build` image.

It installs in `$HOME/vendor/vips` and sets up the appropriate environment
variables.

## Supported stacks

- heroku-24

## Usage

Add this buildpack by running:

```
heroku buildpacks:add https://github.com/mercey-co/heroku-buildpack-vips
```

After running this command you should see the output similar to:

```
Buildpack added. Next release on amazing-earthfest will use:
  1. heroku/ruby
  2. https://github.com/mercey-co/heroku-buildpack-vips
```
