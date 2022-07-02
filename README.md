# Bloatpage

> _A bloated startpage for the modern linux femboy - terribly written, as all open source projects should be. /s_

This is my attempt at a proper startpage that I made myself it's still a work in progess (cause tastes change anyways) and it seems like a pretty good side project to work on.

## Contents

- [Showcase](#showcase)
- [Browser](#browser)
- [Fonts](#fonts)
- [Links](#links)
- [Notes](#notes)

## Showcase
![engine](https://github.com/iwasElitist/bloatpage/blob/main/assets/images/bloatpage.gif)
<p align=center><em>refer to notes for information</em></p>

### Browser

Browser support is currently limited to `IE8+` and a newer version of firefox or whichever chromium-based browser you use because the homepage uses inline SVGs which I don't think support anything under `IE8` as well as `woff2` files for the font used.

Most of the testing is done on qutebrowser, and also do note that this isn't meant for mobile.

### Fonts

`Iosevka Term Web` but you can change them to anything you want anyways by just replacing the font in the css stylesheet in `@font-face` to whatever font you want to use provided its pointing to the right direcctory.

```css
@font-face {
    font-family: "add-font-name-here";
    font-weight: 400; // Modify accordingly
    font-stretch: expanded; // Same with this and add other properties if need be
    font-style: add-font-style;
    src: url("add-font-file-path-here") format("add-font-file-format-here");
}
```

## Links

Whatever you want them to be - given you are willing to change the inline svgs and then change the links in the html via the `<a>` tags.

```html
<a class="websites" href="change-link-here"><svg ... ><path ... change-paths-here ... ></svg></a>
```

## Notes

- On hovering your mouse close to or on the border of the buttons you might notice "_css jitter_" which I haven't been able to find a way to get rid of.
- Because of the current implementation of the buttons which use inline SVGs instead of using the html `<img>`tag there may be a loss of some performance compared to pngs, but hey you don't get the same customizability.
- You can change the wallpaper by changing or modifiying the image file in `assets/images/` to be able to change the name of the file you have to change the name of the sourced file in the `index.html` file.
- The patterns in the gif aren't actually there, the shadows are black as well.
