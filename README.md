# Blog Preview Card

This project is a solution to the **"Blog Preview Card"** challenge on [Frontend Mentor](https://www.frontendmentor.io/). The goal is to recreate a blog preview card based on the provided design, using only **HTML** and **Tailwind CSS**.

## Overview

This challenge focuses on building a responsive blog card layout.

## Technologies Used

- Semantic HTML5
- Tailwind CSS v3+ (via CDN)

## Features

Users should be able to:

- View the blog card properly on both mobile and desktop screens
- See hover and focus states on all interactive elements
- Experience a layout that closely matches the design files

## Personal Goals

- Improve precision when replicating designs
- Use Tailwind CSS classes efficiently and semantically
- Ensure accessibility by using proper HTML structure and attributes

## Getting Started
To view the project locally:

1. Clone the repository:

```bash
git clone git@github.com:AlejaSj/blog-preview-card-main.git
cd blog-preview-card
```
2. Install dependencies
Make sure you have Node.js installed. Then run:

```bash
npm install
```

3. Build Tailwind CSS
To generate the final CSS file using Tailwind CLI:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
4. Open the project
Open ```index.html``` in your browser. Make sure the ```<link>``` points to the compiled CSS file (css/output.css).
This will watch for changes and rebuild the CSS automatically.
