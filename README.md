# Basic Inline CSS Syntax

Inline CSS is written directly inside an HTML tag using the `style` attribute.

## Basic syntax

```html
<tag style="property: value; property: value;">Content</tag>
```

## Example

```html
<p style="color: blue; font-size: 18px;">Hello world</p>
```

## Common CSS properties

- `color` → changes text color
- `background-color` → changes background color
- `font-size` → changes text size
- `font-family` → changes font style
- `margin` → adds space outside an element
- `padding` → adds space inside an element
- `border` → adds border around an element
- `width` → sets element width
- `height` → sets element height

## Example with multiple properties

```html
<div style="background-color: lightgray; padding: 10px; border: 1px solid black;">
  This is a styled box.
</div>
```

## Important notes

- Each property ends with a semicolon `;`.
- Property names and values are separated by a colon `:`.
- Inline CSS is useful for quick styling, but external CSS is better for large projects.
