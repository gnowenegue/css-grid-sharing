---
marp: true
---

<!--
theme: gaia
class: lead
-->

# CSS Grid

---

> CSS Grid is a powerful layout system in CSS that enables the creation of complex, **two-dimensional** grid-based layouts for web pages.

---

# Important CSS Grid Terminology

---

## Grid Container

The element on which `display: grid` is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

```css
.container {
    display: grid
}
```

```html
<div class="container">
  <div class="item item-1"> </div>
  <div class="item item-2"> </div>
  <div class="item item-3"> </div>
</div>
```

---

## Grid Item

The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

```html
<div class="container">
  <div class="item"> </div>
  <div class="item">
    <p class="sub-item"> </p>
  </div>
  <div class="item"> </div>
</div>
```

---

## Grid Line

The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.

![width:500](https://css-tricks.com/wp-content/uploads/2018/11/terms-grid-line.svg)

---

## Grid Track

The space between two adjacent grid lines. You can think of them as the columns or rows of the grid. Here’s the grid track between the second and third-row grid lines.

![width:500](https://css-tricks.com/wp-content/uploads/2021/08/terms-grid-track.svg)

---

## Grid Cell

The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid. Here’s the grid cell between row grid lines 1 and 2, and column grid lines 2 and 3.

![width:500](https://css-tricks.com/wp-content/uploads/2018/11/terms-grid-cell.svg)

---

## Grid Area

The total space surrounded by four grid lines. A grid area may be composed of any number of grid cells. Here’s the grid area between row grid lines 1 and 3, and column grid lines 1 and 3.

![width:500](https://css-tricks.com/wp-content/uploads/2018/11/terms-grid-area.svg)

---

# CSS Grid Properties (Parent)

---

## `grid-template-columns`
## `grid-template-rows`
## `grid-template-areas`
## `grid-template` (shortcut)

---

## `grid-column-gap`
## `grid-row-gap`
## `grid-gap` (shortcut)

---

## `justify-items`
## `align-items`
## `place-items` (shortcut)

<br />

## `justify-content`
## `align-content`
## `place-content` (shortcut)

---

## `grid-auto-columns`
## `grid-auto-rows`
## `grid-auto-flow`

---

## `grid` — shortcut for:

### `grid-template-rows`
### `grid-template-columns`
### `grid-template-areas`
### `grid-auto-rows`
### `grid-auto-columns`
### `grid-auto-flow`

---

# CSS Grid Properties (Children)

---

## `grid-column-start`
## `grid-column-end`
## `grid-column` (shortcut)

<br />

## `grid-row-start`
## `grid-row-end`
## `grid-row` (shortcut)

---

## `grid-area`

---

## `justify-self`
## `align-self`
## `place-self` (shortcut)

---

## Demo

---

## Mondrian

---

# Reference

[A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

---

# Cool Stuff

[1-Line Layouts](https://1linelayouts.glitch.me/)

[GRID GARDEN](https://cssgridgarden.com/)

---

# Thank You