# search-image-gallery

A Polymer Element showing a gallery of image thumbnails and buttons for the search dialog.  Based on image-gallery.

### Example

```js
var images = [{
  id: 1,
  link: 'https://github.com/DigElements',
  name: 'DIG',
  source: 'dig.png'
}, {
  id: 2,
  link: 'https://nextcentury.com',
  name: 'Next Century',
  source: 'NextCentury.png'
}];
```

```html
<search-image-gallery images="[[images]]"></search-image-gallery>
```

### Styling

`<search-image-gallery>` provides the following custom properties and mixins for styling:

Custom property                  | Description                                  | Default
---------------------------------|----------------------------------------------|--------
`--image-gallery-hovering-color` | The background color of the hovering images. | none
`--image-gallery-selected-color` | The background color of the selected images. | none
`--image-gallery-label-style`    | The style of the label.                      | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

