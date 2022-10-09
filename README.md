### What is it?

A simple slider with vanilla CSS & JavaScript. Forked from [itchief/ui-components](https://github.com/itchief/ui-components/tree/master/itc-slider) and refactored.

### Installation

Just copy content of `/slider`, rewrite to your needs, and link to your HTML file.

### Usage

Check out `index.html` to learn about HTML structure.

Set `data-slider` to your sliders to init them automatically.

You can configure them also via dataset properties:

- `data-loop="true/false"` to run in a loop (default: `true`);
- `data-autoplay="true/false"` to swap automatically (default: `false`);
- `data-interval="<milliseconds>"` to set the autoplay interval (default: `5000`);
- `data-refresh="true/false"` to reset on resize event (default: `true`);
- `data-swipe="true/false"` to enable swipe gestures (default: `true`).

To show more that one item at once, just set `max-width` to them in CSS.

### Manual Init

`new Slider(el, config)`

- `el` – DOM-element or its class name
- `config` – config values above in JS object

> To learn more check out [this article \[RU\]](https://itchief.ru/javascript/slider)
