[![Build Status](https://travis-ci.org/advanced-rest-client/paper-checkbox.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/paper-checkbox)  

# paper-checkbox

* Anypoint version of the component **

This element is to be private and used as a replacemenet to any PolymerElements


`<paper-checkbox>` is a button that can be either checked or unchecked.
User can tap the checkbox to check or uncheck it.  Usually you use checkboxes
to allow user to select multiple options from a set.
Avoid using a single checkbox as an option selector and use toggle button intead.
### Example
```
<paper-checkbox>label</paper-checkbox>
<paper-checkbox checked>label</paper-checkbox>
```
### Styling
`<anypoint-checkbox>` provides the following custom properties and mixins for styling:
Custom property | Description | Default
----------------|-------------|----------
`--paper-checkbox` | Mixin applied to the element | `{}`
`--paper-checkbox-input-border-bolor` | Border color of the checkbox input square | `--anypoint-color-aluminum4`
`--paper-checkbox-label-color` | A color of the label. | ` --anypoint-color-steel1`
`--paper-checkbox-label` | Mixin applied to the label | ``
`--paper-checkbox-label-checked-color` | Color of checked label | `--anypoint-checkbox-label-color` or `--anypoint-color-steel1`
`--paper-checkbox-label-checked` | Mixin applie dto checked label | ``
`--paper-checkbox-unchecked-color` | Color of a label of unchecked checkbox | `--anypoint-checkbox-label-color` or `--anypoint-color-steel1`
`--paper-checkbox-error-color` | Color of error state | `--anypoint-color-danger`
`--paper-checkbox-label-spacing` | Spacing between the label and the checkbox | `0`

### Example
```
<paper-checkbox></paper-checkbox>
```

### Styling
`<paper-checkbox>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--paper-checkbox` | Mixin applied to the element | `{}`



### Events
| Name | Description | Params |
| --- | --- | --- |
| change | Fired when the checked state changes due to user interaction. | __none__ |
| iron-change | Fired when the checked state changes. | __none__ |