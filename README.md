# web-2
# Assignment 2: Advanced CSS (Flexbox & Grid)

## Overview
This project demonstrates the use of modern CSS layout techniques, including **Flexbox** and **CSS Grid**, to build a fully structured, responsive single-page web layout. The design features a navigation bar, a card component row, a grid page layout, an interactive image gallery with hover overlays, and a portfolio section.

---

## Task Logic & Layout Breakdown

### Task 0: Navigation Bar (Flexbox)
* **Goal**: Create a horizontal navigation bar with logo and links.
* **Logic**: Uses `display: flex` with `justify-content: space-between` to separate the logo and the links across the horizontal axis. `align-items: center` keeps items vertically centered, and `gap: 20px` provides spacing between navigation links.

### Task 1: Card Row (Flexbox)
* **Goal**: Display equal-width cards in a horizontal row.
* **Logic**: The parent container uses `display: flex` with `gap: 20px`. Each card has `flex: 1`, allowing them to share space equally regardless of screen size. A CSS `transform: translateY(-5px)` on `:hover` provides smooth card lift-up animation.

### Task 2: Layout Areas (CSS Grid Areas)
* **Goal**: Construct a structured page layout using named grid areas.
* **Logic**: Uses `display: grid` combined with `grid-template-areas` (`"header header"`, `"sidebar main"`, `"footer footer"`). Columns and rows are defined via `grid-template-columns` and `grid-template-rows`.

### Task 3: Image Gallery (Grid + Hover Overlay)
* **Goal**: Build a 3x3 image grid with overlay captions on hover.
* **Logic**: Uses `display: grid` with `grid-template-columns: repeat(3, 1fr)`. Each gallery item uses `position: relative` to contain an absolute-positioned `.overlay` element (`position: absolute`). The overlay has `opacity: 0` by default and transitions to `opacity: 1` on hover.

### Task 4: Portfolio Page (Flexbox + Grid)
* **Goal**: Combine Flexbox and Grid for a complex layout structure.
* **Logic**: The outer layout uses CSS Grid (`3fr 1fr`) to separate the main content area from the sidebar. The inner project section uses Flexbox (`display: flex`) to arrange project cards side-by-side.

---

## Technical Highlights
* **Box Model Consistency**: Applied `box-sizing: border-box` globally to include padding and border in overall element sizing.
* **Image Optimization**: Used `object-fit: cover` to maintain image aspect ratios without distortion.
* **Smooth Interactions**: Incorporated CSS `transition` properties for smooth hover animations across cards and overlay elements.

---

## Screenshots

> *Note: Place your task screenshots in an `assets/` or `images/` folder.*

### Task 0: Navigation Bar
<img width="1792" height="90" alt="image" src="https://github.com/user-attachments/assets/8ffaf175-7234-437d-acff-526c7f134d93" />


### Task 1: Cards (Flexbox)
<img width="1772" height="581" alt="image" src="https://github.com/user-attachments/assets/9b3b340e-1859-483c-aff1-78134d3f3786" />


### Task 2: Layout Areas (Grid)

<img width="1767" height="557" alt="image" src="https://github.com/user-attachments/assets/85e6517b-03d9-4e24-963f-fe951af8cb6a" />


### Task 3: Image Gallery (Hover Effect)

<img width="1707" height="725" alt="image" src="https://github.com/user-attachments/assets/d60ad16e-8cde-4689-aefe-4bace5f42753" />


### Task 4: Portfolio Layout

<img width="1671" height="291" alt="image" src="https://github.com/user-attachments/assets/97f1afa2-6981-4453-9ba6-0cc641574c57" />
