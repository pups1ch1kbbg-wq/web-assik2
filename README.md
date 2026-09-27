# Assignment 3: Advanced CSS (Flexbox & Grid)

> **Course:** Front-End Development / Web Technologies  
> **Student Name:** [Kairov Zhangir][cite: 1]  
> **Group:** [SE-2526][cite: 1]  
> **Live Demo:** [GitHub Pages Link / Netlify Link][cite: 1]

---

## 📌 Project Overview
This project showcases modern, responsive CSS layout techniques implemented using **Flexbox** and **CSS Grid** without relying on floats or external frameworks. The repository contains multiple standalone HTML pages, each demonstrating specific alignment, grid area, and layout strategies linked via a unified navigation bar.

---

## 🚀 Navigation & Structure

| Page | File | Layout Concept | Description |
| :--- | :--- | :--- | :--- |
| **Home** | `index.html`[cite: 2] | Flexbox Header/Footer[cite: 2] | Overview of the assignment and student details[cite: 1, 2]. |
| **Task 1** | `task1-flexbox.html`[cite: 3] | Flexbox Layout[cite: 3] | Responsive card container with equal height and hover effects. |
| **Task 2** | `task2-grid-layout.html`[cite: 4] | CSS Grid Areas[cite: 4] | Classic page structure using named grid areas (`header`, `sidebar`, `main`, `footer`)[cite: 1]. |
| **Task 3** | `task3-gallery.html`[cite: 5] | CSS Grid Gallery[cite: 5] | 9-image grid layout with equal columns and interactive hover overlays[cite: 1]. |
| **Task 4** | `task4-portfolio.html`[cite: 6] | Combined Flexbox & Grid[cite: 6] | Grid-based portfolio layout containing cards styled internally with Flexbox[cite: 1]. |

---

## 🛠️ Task Implementations

### Task 0: Navigation Bar
* Implemented a flexible header (`.main-header`) containing a logo aligned to the left and navigation links aligned to the right[cite: 1, 2].
* Utilized `display: flex`, `justify-content: space-between`, and `align-items: center` for alignment across all pages[cite: 1, 2].

### Task 1: Card Row (Flexbox)
* Created a multi-card container (`.card-container`) using Flexbox[cite: 1, 3].
* Ensured uniform height across all cards while preserving consistent gaps (`gap`)[cite: 1].
* Included interactive hover effects (`transform`, `box-shadow`) on each card[cite: 1].

### Task 2: Page Layout (CSS Grid)
* Built a page wrapper using `display: grid`[cite: 1, 4].
* Assigned layout sections using `grid-template-areas`:
  * Header across the top[cite: 1]
  * Sidebar on the left[cite: 1]
  * Main content on the right[cite: 1]
  * Footer across the bottom[cite: 1]

### Task 3: Image Gallery
* Arranged a 9-image responsive grid using `display: grid` and `grid-template-columns`[cite: 1, 5].
* Applied regular spacing using CSS `gap`[cite: 1].
* Added a CSS hover animation that displays a caption overlay over each gallery image[cite: 1, 5].

### Task 4: Portfolio Page (Flexbox + Grid Combination)
* Structured the main page using **CSS Grid** to separate the project showcase area from the sidebar[cite: 1, 6].
* Applied **Flexbox** inside individual project cards to vertically organize the content (title, description, and action button)[cite: 1, 6].
* Created a full-width footer spanning across the bottom of the page layout[cite: 1, 6].

---

## 📂 Directory Tree

```text
.
├── css/
│   └── style.css            # Centralized CSS stylesheet
├── index.html               # Main landing page (Task 0)
├── task1-flexbox.html       # Flexbox card row (Task 1)
├── task2-grid-layout.html   # CSS Grid area layout (Task 2)
├── task3-gallery.html       # CSS Grid image gallery (Task 3)
└── task4-portfolio.html     # Combined Flexbox + Grid portfolio (Task 4)
