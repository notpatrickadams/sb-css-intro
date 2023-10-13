# Part 1 - Conceptual

- What is a CSS selector? Please give an example.
    - A CSS selector is the element that we want to style.
    - Example: `p` or `body`
- What is a CSS Declaration? Please give an example.
    - A CSS declaration is where we define a collection of properties to be applied to an element or set of elements.
    - Example: The `background-color` property is set in this CSS declaration
    ```css
    {
        background-color: chartreuse;
    }
    ```
- What is a CSS Property? Please give an example.
    - A CSS property is an attribute of an element's style that can be changed. In a `.css` file, the "key" in a "key-value" pair.
    - Example: `text-align`
- What is a CSS Value? Please give an example.
    - A CSS value is just that, a value. It is set on a CSS property. In a `.css` file, the "value" in a "key-value" pair.
    - Example: `center`
- What are the three ways to include CSS?
    1. Inline
    2. In a `<style>` tag
    3. Referenced with a `<link>` tag
- What is the difference bettwen rgb and rgba?
    - RGB - the color has no alpha value/is not transparent
        - Set like this: `rgb(r, g, b)`
    - RGBA - the color can have an alpha value and may be transparent
        - Set like this: `rgba(r, g, b, a)`,  where `a` is the alpha value between 0 and 1.
- What is an em?
    - An em was originally the width of the capital letter M in typography. 
    - In CSS, an em can be used to set the font size of an element relative to the font size of its parent.
- What are the differences between em and rem?
    - em
        - relative to the parent element
    - rem
        - relative to the root `<html>` element
- How do you include a Google font?
    1. Find a font from [Google Fonts](https://fonts.google.com)
    2. Include in in your CSS:
        - Include it by copying the `<link>` element and putting it in the `<head>`
        - Include it by copying the `@import` line and putting it at the  top of your CSS file