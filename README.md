# 🌍✈️ Simple Travel Website 

## About This Project

This project is a simple, two-page travel website built using **only fundamental HTML tags**. 

It includes **two linked HTML files** to showcase basic internal navigation.

---

## 🚀 Key Features and Technical Deep Dive

The project consists of two core files, demonstrating various HTML elements:

### 1. `SumitSoni202501100400329.html` (The Main Homepage)

This file serves as the main website content, utilizing several essential HTML tags:

* **Structure:** Uses the correct HTML5 `<!DOCTYPE html>`, with clear `<head>` (metadata) and `<body>` (visible content) sections. Headings (`<h1>` and `<h2>`) establish a clear content hierarchy.
* **Formatting:** Paragraphs are formatted using all basic inline tags:
    * `<b>` (Bold)
    * `<i>` (Italic)
    * `<u>` (Underline)
    * `<s>` (Strikethrough)
* **Images (`<img>`):** Images for favorite destinations (Goa and Shimla) and activities are included.
    > ⚠️ **Note on Images:** Two image paths are **relative** (e.g., `src="/HTML assignment/..."`). They will only load correctly if the original folder structure (including the **/HTML assignment/** parent folder) is preserved.
* **Hyperlinks (`<a>`):**
    * **External Link:** Links to an external site (MakeMyTrip), using `target="_blank"` to open in a new tab.
    * **Internal Link:** Links to the `Contact Us .html` page for navigation.
* **Lists:** Examples of all three primary list types are included:
    * **Ordered List (`<ol>`):** Used for **Top Destinations**.
    * **Unordered List (`<ul>`):** Used for **Travel Essentials**.
    * **Definition List (`<dl>`):** Used for **Travel Meanings** (`<dt>` for Term, `<dd>` for Definition).
* **Table (`<table>`):** A simple package cost table, using the `border="1"` attribute to display the grid visually.

### 2. `Contact Us .html` (The Linked Page)

This simple, minimal page is included to demonstrate successful **internal hyperlink navigation** back to the main homepage, ensuring two-way linking works correctly within the project.

---

## 🛠️ How to Run This Project Locally

This is a simple, client-side project, making it very easy to launch:

1.  **Clone or Download:** Get all project files onto your local machine.
2.  **Verify Structure:** Ensure both `SumitSoni202501100400329.html` and `Contact Us .html` are located **inside** the `/HTML assignment/` directory, as the internal links depend on this path.
3.  **Launch:** Simply **double-click** the main file: **`SumitSoni202501100400329.html`**
4.  The file will open in your default web browser. You can then test the internal navigation (Contact Us link) and the external hyperlink.
