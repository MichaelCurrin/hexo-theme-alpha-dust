# Alpha Dust Hexo Blog Theme

![](http://www.codeblocq.com/img/hexo-theme-thumbnail/AlphaDust.jpg)

[Check out the demo](http://www.codeblocq.com/assets/projects/hexo-theme-alpha-dust/).

This theme was developed from scratch by myself just for fun. It is a glowy futuristic theme, hope you will find a use for it :)

## Features Overview

- Responsive
- Disqus comments
- Google Analytics
- Tags Support
- Responsive Images
- Responsive YouTube and Vimeo videos
- Image Gallery
- Social Accounts configuration
- Pagination
- Pages
- Only one category per post
- Stylus CSS preprocessor
- ejs HTML templates

## External libraries used

- [Bootstrap 4 Alpha](http://v4-alpha.getbootstrap.com/) 
- [FeatherLight.js](http://noelboss.github.io/featherlight/) (Gallery)
- [jQuery](https://jquery.com/)
- [GSAP](http://greensock.com/gsap)
- [Font Awesome](http://fontawesome.io/icons/)

## Installation

### Install the theme

Install the theme by using:

```sh
$ git submodule add https://github.com/klugjo/hexo-theme-alpha-dust themes/alpha-dust
```

Then update your blog's main `_config.yml` to set the theme to `alpha-dust`:

```yaml
theme: alpha-dust
```

## Theme Configuration

The theme's global configuration is done in `/themes/hexo-theme-alpha-dust/_config.yml`.

### Menu

The menu is configured in the theme's `_config.yml`.

```yaml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about.html
```

The object key is the label and the value is the path.

### Blog's Logo Image Source

The blog's logo (above the title) is configured in the theme's `_config.yml`.

The value should be a valid [Font Awesome class](http://fontawesome.io/icons/)

```
# Logo (Font Awesome Class)
fa_logo: fa-cube
```

Page's and post's logo is configured in front matter and overrides blog's logo if defined.

```yaml
---
title: Post's title
logoIcon: fa-pencil-square
---
```

### Footer About Section Text

The About section's text in the footer is configured in the theme's `_config.yml`. HTML allowed.

```yaml
# Footer About Text
footer_about: "Make Websites. Make Magic."
```

### Footer Copyright Section Text

The Copyright section's text in the footer is configured in the theme's `_config.yml`. HTML allowed.

```
#Footer Copyright Line
footer_copyright: "@Untitled. All right reserved | Design & Hexo <a href=\"http://www.codeblocq.com/\">Jonathan Klughertz</a>"
```

### Default post title

The default post title (used when no title is specified) is configured in the theme's `_config.yml`.

```yaml
# Default post title
default_post_title: Untitled
```

### Archive Date Format

You can change the date format for the archive page if you so desire

```yaml
# Archive Date Format
archive_date_format: MMM YYYY
```

### Disqus Comments

The disqus shortname is specified in the theme's `_config.yml`.

```yaml
# Comments.
comments:
  # Disqus comments
  disqus_shortname: klugjotest
```

### Google Analytics

The Google Analytics Tracking ID is configured in the theme's `_config.yml`.

```yaml
# Google Analytics Tracking ID
google_analytics:
```

### Social Account

Setup the links to your social pages in the theme's `_config.yml`. Links are in the footer. No link = No icon.

```yaml
# Social Accounts
twitter_url: https://twitter.com/?lang=en
facebook_url: https://www.facebook.com/
instagram_url: https://www.instagram.com/
dribble_url: https://dribbble.com/
github_url: https://github.com/klugjo/hexo-theme-alpha-dust
googleplus_url: https://plus.google.com/
behance_url: https://www.behance.net/
fivehundredpx_url: https://500px.com/
email_url: \#
rss_url: \#
```

## Tags page.

> Follow these steps to add a `tags` page that contains all the tags in your site.

- Create a page named `tags`

```sh
$ hexo new page "tags"
```

- Edit the newly created page and set page type to `tags` in the front matter.

```yaml
title: All tags
type: "tags"
```

- Add `tags` to the menu in the theme `_config.yml`:

```yaml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about.html
  Tags: /tags
```

## Categories page.

> Follow these steps to add a `categories` page that contains all the categories in your site.

- Create a page named `categories`

```sh
$ hexo new page "categories"
```

- Edit the newly created page and set page type to `categories` in the front matter.

```sh
title: All tags
type: "categories"
```

- Add `tags` to the menu in the theme `_config.yml`:

```yaml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about.html
  Categories: /categories
```

## Creator

This theme was created by Jonathan Klughertz, check out my [github](https://github.com/klugjo) and [blog](http://www.codeblocq.com/) for more info.

## Bugs

If you have a question, feature request or a bug you need me to fix, please [click here](https://github.com/klugjo/hexo-theme-phantom/issues/new) to file an issue.

## License

Source license - [MIT](https://github.com/klugjo/hexo-theme-alpha-dust/blob/master/LICENSE).
