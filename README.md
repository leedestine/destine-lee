# Project Name: News Website - KEERY K-Pop News Portal

## Project Structure

```
project-name/
├── index.html         # Homepage (Main Entry Point)
├── article1.html      # News Article Page
├── css/               # All CSS files
│   ├── style.css       # Main global stylesheet (typography, resets, layout)
│   ├── utility-styles.css  # Reusable utility classes (e.g., flex, margins, colors)
│   ├── article1.css    # Specific styles for the article page
├── images/            # Image Assets
│   ├── logo.png        # Site logo
│   ├── hero.jpg        # Hero image
│   ├── product1.jpg    # Example product image
│   ├── ...            # Other images
└── README.md          # Project description and instructions
```

## Overview
This project is a **news website** consisting of a homepage and an article page. The site is styled using reusable utility classes, global styles, and page-specific styles.

## Files and Directories

### 1. `index.html` (Homepage)
- Displays the main news feed.
- Includes a **hero section** with a headline of the breaking news and a featured image.
- Contains a **hamburger menu toggle** which will re-direct to the second page `article1.html`.
- Contains a **responsive navigation bar** with a search bar and sign-in options.
- Contains a **logo** in the center of the navbar which allow user to link to the home page (`index.html`).

### 2. `article1.html` (News Article Page)
- Displays the **headline in the home page** with a title, content, images, and  comments.
- Includes a **comment section** where users can view and post comments.
- Uses styles from `article1.css` for layout and typography specific to news articles.
- Follows **responsive design** principles.

### 3. `css/style.css` (Main Global Stylesheet)
- Defines the **site-wide typography, layout, and global styles**.
- Styles the **navigation bar, buttons, hero section, and footer**.
- Ensures responsiveness with **media queries**.

### 4. `css/utility-styles.css` (Reusable Utility Classes)
- Contains **flexbox utilities** for alignment.
- Includes **margin and padding utilities** for spacing consistency.
- Defines **color classes** for text and backgrounds.
- Provides **text formatting utilities** (bold, italic, centered text, etc.).
- Contains **border utilities** for styling elements.
- Uses **display utilities** (`block`, `inline-block`, `hidden`).

### 5. `css/article1.css` (Article Page Specific Styles)
- Custom styles specific to the **news article layout**.
- Styles for **comment sections**, ensuring profile images and text are properly aligned.
- Ensures the article page **remains responsive on different screen sizes**.

## Features
✅ **Responsive Design:** Ensures the website adapts to different screen sizes.
✅ **Navigation Bar:** Includes a **hamburger menu** for mobile screens.
✅ **Search Functionality:** Clickable search bar for easy navigation.
✅ **Hero Section:** Displays a featured news story.
✅ **Utility Styles:** Reusable CSS classes for **flexbox, spacing, colors, and typography**.
✅ **Comment Section:** Users can view and post comments with profile images.

## How to Run the Project
1. Download the project files.
2. Open `index.html` in a web browser.
3. Click on a news article to navigate to `article1.html`.
4. Adjust the browser size to test **responsive design**.


**Author:** Destine Lee 
**Date:** 2025  
**License:** University of  Arizona

