# Bloatpage

> _A bloated startpage for the modern linux femboy. Terribly written, as all open source projects should be._

Although the first part was a joke the actual source code might not be too far off from it so if you find it interesting... Well you'll have to deal with it yourself. You could file issues but I probably won't fix them anyways.

This is my attempt at a proper startpage that I made myself it's still a work in progess (cause tastes change anyways) and it seems like a pretty good side project to work on.

----------------

## Contents

- [Dependencies](#dependencies)
    - [Browser](#browser)
    - [Fonts](#fonts)
- [Links](#links)
- [Gallery](#gallery)
- [Notes](#notes)

----------------

## Dependencies

### Browser

Browser support is currently limited to `IE8+` because the homepage uses inline SVGs which I don't think support anything under `IE8`.


### Fonts

`Iosevka Term Web` but you can change them to anything you want anyways by just replacing the font in the css and changing the stylesheet from `iosevka-term.css` to whatever font you want to use provided its in the right direcctory. Icon fonts are also probably going to be useful to install because they would help you actually be able to see the icons, again `Iosevka Term Web` might work but it's probably better to _nip the bud early_ (or something like that).

----------------

## Links

Whatever you want them to be - given you are willing to change the icons in the inline svgs and then change the links in the html via the `<a>` tags.

----------------

## Gallery

| ![bloatpage](https://raw.githubusercontent.com/iwasElitist/bloatpage/main/screenshots/2022-05-17-072338_1920x1080_scrot.png?raw=true "normal") | 
| --- |
| <p align="center">On opening the page</p> |

| ![bloatpage](https://raw.githubusercontent.com/iwasElitist/bloatpage/main/screenshots/2022-05-17-072504_1920x1080_scrot.png?raw=true "icon hover") |
| --- |
| <p align="center">On icon hover</p> |

| ![bloatpage](https://raw.githubusercontent.com/iwasElitist/bloatpage/main/screenshots/2022-05-17-072800_1920x1080_scrot.png?raw=true "search bar") |
| --- |
| <p align="center">On text input and search hover</p> |

----------------

## Notes

- On hovering your mouse close to or on the border of the buttons you might notice "_css jitter_" it is a recurring issue which I still haven't been able to find a way to get rid of.
- Because of the current implementation of the buttons which use inline SVGs instead of using the html `<img> `tag

----------------
