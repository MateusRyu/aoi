# aoi
personal blog

## Usage

### Build
Builds the site and outputs a static site to a directory called `_site`.

```sh
bundle exec jekyll build
```

### Serve
Does `jekyll build` and runs it on a local web server at `http://localhost:4000`, rebuilding the site any time you make a change.

```sh
bundle exec jekyll serve
```

To force the browser to refresh with every change, use `bundle exec jekyll serve --livereload`. If there’s a conflict or you’d like Jekyll to serve your development site at a different URL, use the `--host` and `--port` arguments, as described in the serve command options.