# Chidera's Lab 2

Simplistic jekyll portfolio-style theme for writers.

**Demo**: [thelehhman.com](https://thelehhman.com)

![plainwhite theme preview](/screenshot.png)


## Installation on Github Pages

Add this line to your site's `_config.yml`:
```yaml
remote_theme: thelehhman/plainwhite-jekyll
```
## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "plainwhite"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: plainwhite
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install plainwhite

## Usage

The "plainwhite" key in _config.yml is used to customize the theme data.
```yaml
plainwhite:
  name: Adam Denisov
  tagline: Developer. Designer
  date_format: "%b %-d, %Y"

  social_links:
    twitter: thelehhman
    github:  thelehhman
    linkedIn: in/thelehhman # format: locale/username
```

**Updating Placeholder Image**

The placeholder portfolio image can be replaced by the desired image by placing it as `assets/portfolio.png` in your jekyll website.

**Comments (Disqus)**

Comments on posts can be enabled by specifying your disqus_shortname under plainwhite in `_config.yml`. For example,
```yaml
plainwhite:
  disqus_shortname: games
```

**Google Analytics**

It can be enabled by specifying your analytics id under plainwhite in `_config.yml`
```yaml
plainwhite:
  analytics_id: '< YOUR ID >'
```

**Sitemap**

It can be toggled by the following line to under plainwhite in  `_config.yml`

```yaml
plainwhite:
  sitemap: true
```

**Excerpts**

Excerpts can be enabled by adding the following line to your `_config.yml`
```yaml
show_excerpts: true
```
**Layouts**

- Home
- Page
- Post

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/thelehhman/plainwhite-jekyll. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `plainwhite.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## More themes

- [Texture](https://github.com/thelehhman/texture)
