# detail-subsection

A Polymer Element showing a subsection with optional header, extractions, detail, or link.

### Example
```html
<detail-subsection
  header="Section Title"
  entity-id="1234"
  extractions="[[extractions]]"
  detail="The quick brown fox jumped over the lazy dog.">
</detail-subsection>
```

### Styling

`<detail-subsection>` provides the following custom properties and mixins for styling:

Custom property          | Description                      | Default
-------------------------|----------------------------------|--------
`--primary-text-color`   | The color of the icons and text. | --primary-text-color
`--secondary-text-color` | The hover color of the links.    | --secondary-text-color

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

