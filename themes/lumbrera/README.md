# Lumbrera

## Configuration

``` yml
# Header
menu:
  Home: /
rss: /atom.xml

# Content
excerpt_link: Read More

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
github:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID
- **github** - Github User

## Development

### Requirements

- [Grunt] 0.4+
- Hexo 2.4+

### Grunt tasks

- **default** - Download [Bulma] and [Font Awesome].
- **fontawesome** - Only download [Font Awesome].
- **bulma** - Only download [Bulma].
- **clean** - Clean temporarily files and downloaded files.

[Hexo]: https://hexo.io/
[Bulma]: https://bulma.io/
[Font Awesome]: http://fontawesome.io/
[Grunt]: http://gruntjs.com/
[hexo-generate-feed]: https://github.com/hexojs/hexo-generator-feed
