# Cloud Castle: HTML & CSS style guide

### CSS
* Do not use cascade with more than 2 levels;
* Do not use html tags as selectors. Use css classes. (exceptions: tables);
* Do not add vendor prefixes in css, use [autoprefixer](https://github.com/postcss/autoprefixer);
* Always [use transform: translate](http://www.html5rocks.com/en/tutorials/speed/high-performance-animations/), instead of margin/padding/left/top for position animations;
* Do not use css selectors in js and js selectors in css;

### Images
* All icons should be retina-ready (raster images should be x2, preferably use svg);
* All applications should have a favicon, also retina-ready;
* All icons should be inlined in css, using `url(data:...)` in order to requce count of requests to server;

### HTML
* Do not use links with `href=“javascript: void”`, `href="#"`, etc.
* Add `tabindex="0"` for all custom form elements;
* Add `download` attribute to all download links, like `<a href="source" download="report.pdf">`;
* Add `title` attribute to links and buttons w/o text description and to clipping labels & one-liners (e.g. when user name clips due to width restrictions);

### Usability
* Always add `:focus` and `:active` states for links, buttons and form elements;
