# jekyll-commonmark

*CommonMark Markdown converter for Jekyll*

[![Gem Version](https://img.shields.io/gem/v/jekyll-commonmark.svg)](https://rubygems.org/gems/jekyll-commonmark)
[![Build Status](https://img.shields.io/travis/pathawks/jekyll-commonmark/master.svg)](https://travis-ci.org/pathawks/jekyll-commonmark)
[![Dependency Status](https://img.shields.io/gemnasium/pathawks/jekyll-commonmark.svg)](https://gemnasium.com/pathawks/jekyll-commonmark)

Jekyll Markdown converter that uses [libcmark](https://github.com/jgm/CommonMark), the reference parser for CommonMark.

## Installation

Add the following to your `Gemfile`

```ruby
group :jekyll_plugins do
  gem 'jekyll-commonmark', :github => 'pathawks/jekyll-commonmark'
end
```

and modify your `_config.yml` to use **CommonMark** as your Markdown converter

```yaml
markdown: CommonMark
```
