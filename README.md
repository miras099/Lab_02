# Lab 02 – JSX, Fragments & Expressions

Student: Bereket  
Course: React Development  
Week: 2  

---

## 📌 Overview

This lab focuses on:

- Using JSX
- React Fragments (<>...</>)
- JavaScript expressions in JSX
- Mapping arrays to lists
- Creating reusable components
- Passing dynamic props

The lab consists of two parts: task1 and task2.

---

# 🔵 Task 1 – Fragments & List Mapping

Location:
Lab_02/task1/

### Implemented Components:

### 1️⃣ FragmentLayout.jsx
- Returns exactly three sibling elements:
  - `<header>`
  - `<main>`
  - `<footer>`
- Uses React Fragment `<>...</>`
- No extra wrapper `<div>`

### 2️⃣ ItemList.jsx
- Defines an array of items
- Uses `.map()` to render list
- Each `<li>` has a unique `key`
- Displays item data using JSX expressions `{}`

### 3️⃣ Combined.jsx
- Uses Fragment
- Renders:
  - `<h2>` title
  - list generated with `.map()`
  - summary paragraph
- Displays total using `{items.length}`

---

# 🔵 Task 2 – Custom Components & Props

Location:
Lab_02/task2/

### Implemented Components:

### 1️⃣ Card.jsx
- Accepts props:
  - `title`
  - `children`
  - `className`
- Uses JSX expressions for dynamic values
- Reusable component

### 2️⃣ ProductList.jsx
- Defines products array
- Uses `.map()` to render products
- Uses `key={product.id}`
- Displays dynamic data with `{}`

### 3️⃣ Section.jsx
- Uses React Fragment
- Accepts:
  - `title`
  - `children`
- Composed in App component
