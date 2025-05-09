---
title: "StyleSheet: disabled property"
short-title: disabled
slug: Web/API/StyleSheet/disabled
page-type: web-api-instance-property
browser-compat: api.StyleSheet.disabled
---

{{APIRef("CSSOM")}}

The **`disabled`** property of the
{{domxref("StyleSheet")}} interface determines whether the style sheet is prevented from
applying to the document.

A style sheet may be disabled by manually setting this property to `true` or
if it's an inactive [alternative style sheet](/en-US/docs/Web/HTML/Reference/Attributes/rel/alternate_stylesheet). Note that `disabled === false` does not guarantee the style
sheet is applied (it could be removed from the document, for instance).

## Value

A boolean.

## Examples

```js
// If the stylesheet is disabled
if (stylesheet.disabled) {
  // Apply styles in-line
}
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
