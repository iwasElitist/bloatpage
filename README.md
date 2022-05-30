# Bloatpage

> _A bloated startpage for the modern linux femboy - terribly written, as all open source projects should be. /s_

This is my attempt at a proper startpage that I made myself it's still a work in progess (cause tastes change anyways) and it seems like a pretty good side project to work on.

## Contents

- [Dependencies](#dependencies)
    - [Browser](#browser)
    - [Fonts](#fonts)
- [Links](#links)
- [Gallery](#gallery)
- [Notes](#notes)

## Dependencies

### Browser

Browser support is currently limited to `IE8+` and a newer version of firefox or whichever chromium-based browser you use because the homepage uses inline SVGs which I don't think support anything under `IE8` as well as `woff2` files for the font used.


### Fonts

`Iosevka Term Web` but you can change them to anything you want anyways by just replacing the font in the css stylesheet in `@font-face` to whatever font you want to use provided its pointing to the right direcctory.

## Links

Whatever you want them to be - given you are willing to change the icons in the inline svgs and then change the links in the html via the `<a>` tags.

## Gallery

| ![bloatpage](https://raw.githubusercontent.com/iwasElitist/bloatpage/main/screenshots/onopening.png?raw=true "normal") | 
| --- |
| <h4 align="center">_On opening the page_</h4> |

| ![bloatpage](https://raw.githubusercontent.com/iwasElitist/bloatpage/main/screenshots/onhover.png?raw=true "icon hover") |
| --- |
| <h4 align="center">_On icon hover_</h4> |

| ![bloatpage](https://raw.githubusercontent.com/iwasElitist/bloatpage/main/screenshots/onsearching.png?raw=true "search bar") |
| --- |
| <h4 align="center">_On text input and search hover_</h4> |

## Notes

- On hovering your mouse close to or on the border of the buttons you might notice "_css jitter_" it is a recurring issue which I still haven't been able to find a way to get rid of.
- Because of the current implementation of the buttons which use inline SVGs instead of using the html `<img> `tag
