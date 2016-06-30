# Disappointment
Disappointment is a customized minimalistic [Ghost](https://ghost.org/) theme inspired by
[KISS](https://github.com/calincru/KISS).

![Disappointment Mockup](http://i.imgur.com/q5sRMIk.jpg)

Check it out on [my blog](http://quangteomedia.com).

## Features
- Minimalistic & responsive
- Google Analytics
- Disqus comments
- 46 Social icons ([Fontello](http://fontello.com))
- Minified assets
- Code syntax highlighting (via [Prismjs](http://prismjs.com))
- Script for easy updating

## SEO
- Post tags as meta keywords
- Structured Data (passed Google Structured Data Testing Tool)

## // TODO
- ...

## Installation
* Goto your ghost theme directory

```bash
cd /path/to/ghost/content/themes
```

* Clone this repo

```bash
git clone https://github.com/quangtt/Disappointment.git
```
```bash
cd disappointment
```
```bash
npm install
```
```bash
./node_modules/.bin/gulp
```

* Have fun!

## Configuration
Make sure you modify all my personal stuff, such as:
- Social links (`social.hbs`)
- Google Analytics tracking code (`analytics.hbs`) ([sign
  up](https://accounts.google.com/ServiceLogin?service=analytics&userexp=signup&hl=en)
  and they will provide the whole new JS code)
- Disqus shortname (`disqus.hbs`)
- Blog cover: if you don't set your own cover, it'll show mine :)

## Check for update

If you have already installed the theme, you can update it executing

```bash
sh update.sh
```

## Preview

**Desktop view**

![Desktop view](http://i.imgur.com/VuP8bZ9.jpg)

**Desktop view (single post)**

![Desktop post view](http://i.imgur.com/3OZo5DR.jpg)

**Mobile view**

![Mobile view](http://i.imgur.com/iDFCXot.jpg)

**Mobile view (single post)**

![Mobile post view](http://i.imgur.com/WMHDZqh.jpg)
