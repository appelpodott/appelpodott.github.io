# jekyll-theme-redux

[![Gem Version](https://badge.fury.io/rb/jekyll-theme-redux.svg)](https://badge.fury.io/rb/jekyll-theme-redux)

An absurdly bare-bone Jekyll theme. Inspired by [Poole][poole].

Use it as is or as a launchpad for your own creations. See it [live][demo].

![Screen Shot](/screenshot.png "Let the browser do the heavy lifting.")

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-redux"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-redux
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-redux

### Configuration

The following `_config.yml` options are leveraged:

```yaml
author: # information about the author
  name: # the author's name
  url:  # the author's homepage url

navigation: # a collection of links to display in the masthead
  - title: About
    url: /about
```

## Changelog

The changelog can be consulted [here][changelog].

## License

The theme is available as open source under the terms of the [MIT License][license].

[poole]: https://github.com/poole/poole
[demo]: https://laurentboileau.github.io/jekyll-theme-redux
[changelog]: CHANGELOG.md
[license]: LICENSE.txt
