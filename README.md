<p align="center">
<img src="logo_shaded_alpha.png">
</p>

# MagCMS

MagCMS is static website and content generator for modern company websites.

Based on: Prosopopee. Static site generator for your story.

Make beautiful customizable company sites, landing pages or pictures galleries that tell a story using a static website generator written in Python. You don't need to care about css, code and presentation, manage your contents in YAML file and MagCMS will take care about the rest.

MagCMS is sections oriented, make it very flexible, many kinds of section already available:

* Parallax
* Group of pics (gallery)
* Paragraph
* Iframe (Youtube, Maps, etc..)
* Quote
* "subgal-section" which leads to subpages shown as a gallery
* And many more. 

# Documentation

Currentl no fancy documentation, but you can access the source code for the website of my company MagosIT Kft.

See: [magosit-website] (https://github.com/magosit-website)

You can also try browsing the original [prosopopee docs](http://prosopopee.readthedocs.io/en/latest/sections.html)

[More docs] (http://prosopopee.readthedocs.org/en/latest/)

## Features

MagosCMS currently supports:

 * Lightweight and fast
 * Hackable for your own needs
 * Thumbnails & multiple resolutions for fast previews (JPEG progressive)
 * Videos support
 * Mobile friendly
 * Caching for fast rendering
 * Multi level gallery
 * Support for themes (**only the default theme works for now**)
 * Password access (encrypt page)
 * Image lazy loading
 * Night Mode
 * Completely static output is easy to host anywhere
 
## Examples
 
Example website:

 * [www.magosit.hu - under construction] (www.magosit.hu)
 
 ## Code example

```yaml
title: Title
date: 2015-12-18
cover: P1070043-01-01.jpeg
sections:
  - type: full-picture
    image: P1060979-01-01.jpeg
    fixed: true
    text:
      title: My Story
      sub_title: some subtitle
      date: 2015-12-18
  - type: paragraph
    title: Beautiful Title
    text: Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor
  - type: pictures-group
    images:
      -
        - P1060938-01-01.jpeg
        - P1060946-01-01.jpeg
        - P1060947-01-01.jpeg
        - P1060948-01-01.jpeg
```
 
## Usage

Currently its executable is still named prosopopee.

TODO: rename this!

```bash
prosopopee
prosopopee preview
prosopopee deploy
prosopopee test
prosopopee (-h | --help)
prosopopee.py --version
```

## Licence 

GLPv3 - just like the orginal prosopopee!

## Why a fork?

I have actually asked the original creator of prosopopee if he would like my changes or if I should fork this off. His original project is much more aimed at photo gallery sites while mine is aimed at creating44
