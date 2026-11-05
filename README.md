# Gallery & Feedback Form

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-Build%20Tool-purple?style=flat-square&logo=vite&logoColor=white)
![SimpleLightbox](https://img.shields.io/badge/SimpleLightbox-Gallery-lightgrey?style=flat-square)
![LocalStorage](https://img.shields.io/badge/Web%20Storage-localStorage-blue?style=flat-square)

## Overview

This project contains two browser-based JavaScript tasks built with Vite: an interactive image gallery and a feedback form with persistent state.

## Tech Stack

- JavaScript
- HTML
- CSS
- Vite
- SimpleLightbox
- LocalStorage
- Git & GitHub

## Features

### Image Gallery

- dynamically renders image cards from JavaScript data;
- opens full-size images in a SimpleLightbox modal;
- connects preview images with original versions;
- includes image descriptions.

### Feedback Form

- tracks email and message fields;
- saves form state to `localStorage` while the user types;
- restores saved values after page reload;
- validates that both fields are completed before submission;
- clears stored data and resets the form after successful submission.

## Running Locally

```bash
npm install
npm run dev
```

## Live Demo

[Open GitHub Pages](https://dashakim2209.github.io/goit-js-hw-09/)

## Learning Outcomes

- working with third-party libraries;
- browser storage with `localStorage`;
- JSON serialization;
- DOM events and form handling;
- modular JavaScript;
- Vite-based project setup.
