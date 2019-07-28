---
filename: /packages/material-ui/src/StepIcon/StepIcon.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# StepIcon API

<p class="description">The API documentation of the StepIcon React component. Learn more about the properties and the CSS customization points.</p>

```js
import { StepIcon } from '@material-ui/core';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">active</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | Whether this step is active. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">completed</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | Mark the step as completed. Is passed to child components. |
| <span class="prop-name">error</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | Mark the step as failed. |
| <span class="prop-name required">icon&nbsp;*</span> | <span class="prop-type">node</span> |  | The icon displayed by the step label. |

The `ref` is forwarded to the root element.

Any other properties supplied will be provided to the root element (native element).

## CSS

- Style sheet name: `MuiStepIcon`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">MuiStepIcon-root</span> | Styles applied to the root element.
| <span class="prop-name">text</span> | <span class="prop-name">MuiStepIcon-text</span> | Styles applied to the SVG text element.
| <span class="prop-name">active</span> | <span class="prop-name">MuiStepIcon-active</span> | Pseudo-class applied to the root element if `active={true}`.
| <span class="prop-name">completed</span> | <span class="prop-name">MuiStepIcon-completed</span> | Pseudo-class applied to the root element if `completed={true}`.
| <span class="prop-name">error</span> | <span class="prop-name">Mui-error</span> | Pseudo-class applied to the root element if `error={true}`.

You can override the style of the component thanks to one of these customizability points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If it's not enough, you can find the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/StepIcon/StepIcon.js) for more detail.

## Notes

The component is fully [StrictMode](https://reactjs.org/docs/strict-mode.html) compatible.

## Demos

- [Steppers](/components/steppers/)
