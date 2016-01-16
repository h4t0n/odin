# Odin

![Ghost version](https://img.shields.io/badge/Ghost-0.7.x-brightgreen.svg?style=flat-square)
[![Donate](https://img.shields.io/badge/donate-paypal-003087.svg?style=flat-square)](https://www.paypal.me/andreatarquini/5)

> A simple theme for Ghost made for geeks, hackers and developers (forked from Casper).

[<img src="http://i.imgur.com/SjCzgwp.jpg">](https://blog.h4t0n.com)

***Do you like my theme? Do you want new features?***  
Great, we can discuss. Open a pull request. Some :coffee::coffee::coffee::coffee: offered with [Paypal](https://www.paypal.me/andreatarquini/5) are appreciated.

## Intro
**Odin** is a very simple fork of the Ghost default theme [Casper](https://github.com/TryGhost/Casper).
As you know, Casper doesn't have some nice features very useful for developers such as syntax
highlight, comments and big social sharing features. So I created this theme to fill the gap
but keeping all the good and minimalistic features of Casper.



### Features
* Casper minimalistic and clean style (without right side menu)
* Works with Ghost 0.7+
* Fully responsive (for mobiles and tablets)
* Google Analytics (easily configurable by code injection in the admin area)
* [Disqus](https://disqus.com) comments (easily configurable by code injection in the admin area)
* [Prism](http://prismjs.com/) Syntax Highlight (all languages supported)
* [RRSSB](https://github.com/kni-labs/rrssb) Extraordinary Social Sharing Buttons

### Demo
I've created and I use this theme for my personal blog at [blog.h4t0n.com](https://blog.h4t0n.com).

## Installation
Installation is the same as other themes, so clone this repo inside your Ghost `content/themes/` folder.

```
# for example
$ cd /your-ghost-root-directory
$ git clone https://github.com/h4t0n/odin.git content/themes/odin
```

Restart Ghost and select Odin theme from your Admin Area.

## Configuration
No need to configure ***Prism*** or ***RRSSB*** buttons.

***Disqus*** comments and ***Google Analytics*** are disabled by default, but they are easily configurable with *Blog Header Code Injection* inside your Ghost Admin Area.

```html
<script>
// to enable Google Analytics
var ga_id = 'YOUR-UA-ID_HERE';

// to enable Disqus
var disqus_shortname = 'YOUR_DISQUS_SHORTNAME'
</script>
```


## Copyright & License

Released under the MIT License.  
Copyright (c) [Andrea Tarquini](https://blog.h4t0n.com) aka [@h4ton](https://twitter.com/h4t0n)  
Copyright (c) 2013-2015 Ghost Foundation (for Casper theme substantial portions of code)
