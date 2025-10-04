# YouTube Layout + Flex & Grid Practice

A small front‑end practice repo featuring a mini YouTube-style layout plus three focused practice files for **Flexbox** and **CSS Grid**. The goal was to get comfortable with modern layout techniques and then apply them in a slightly larger UI.

## 📁 Project Structure

```
.
├── index.html               # YouTube-like layout (header, sidebar, responsive video grid)
├── youtube.css              # Styles for the main layout (header/sidebar/grid responsiveness)
├── flex-practice.html       # Small Flexbox experiments (axes, flex, gaps, alignment)
├── flexbox.html             # Simple top nav built with Flexbox (Home • Search • Download)
└── grid-practice.html       # Grid experiments (fixed tracks, fr units, gaps)
```

- Main page markup and Google Fonts setup are in `index.html`. fileciteturn0file0  
- Responsive grid, header/sidebar, tooltips, and media queries live in `youtube.css`. fileciteturn0file1  
- Flexbox fundamentals (row layouts, `flex: 1/2`, `justify-content`, `align-items`) are in `flex-practice.html`. fileciteturn0file2  
- A compact Flexbox navbar (space-around, max-width center search) is in `flexbox.html`. fileciteturn0file3  
- Grid basics (fixed + fractional columns, `column-gap`/`row-gap`) are in `grid-practice.html`. fileciteturn0file4

## 🚀 Getting Started (Local)

1. **Clone** the repo and open it in your editor:
   ```bash
   git clone <your-repo-url>.git
   cd <your-repo-folder>
   ```
2. **Open** any of the HTML files directly in your browser (no build step required):
   - `index.html` → full YouTube-style page
   - `flex-practice.html` → Flexbox demos
   - `flexbox.html` → Flexbox navbar
   - `grid-practice.html` → Grid demos

> Tip: If you use VS Code, install **Live Server** and click “Go Live” for auto‑reload.

## 🧱 What This Project Demonstrates

- **Flexbox**: horizontal rows, flexible columns using `flex: 1/2`, spacing with `justify-content: center/space-between/space-around`, vertical centering with `align-items: center`. fileciteturn0file2 fileciteturn0file3
- **CSS Grid**: track definitions mixing fixed px and fractional `fr` units, responsive card grids, and grid gaps. fileciteturn0file1 fileciteturn0file4
- **Responsive layout**: media queries adapt the video grid from 2 → 3 → 4 columns. fileciteturn0file1
- **Sticky UI regions**: fixed header and fixed left sidebar similar to YouTube’s layout. fileciteturn0file1
- **Accessible basics**: visible focus on the search input and adequate color contrast for badges/tooltips. fileciteturn0file1

## 🧩 Notes & Assets

- The main page references the **Roboto** web font via Google Fonts. fileciteturn0file0
- Icons/imagery are referenced from `icons/`, `thumbnail/`, and `profile photo/` folders. Add your own assets with the same filenames or update the image `src` URLs in the HTML. fileciteturn0file0
- **Path check:** `index.html` currently links to `Styles/youtube.css`. If your CSS file is at the project root as `youtube.css`, either move it into a `Styles/` folder or update the `<link>` href to `youtube.css`. fileciteturn0file0 fileciteturn0file1

## 📐 Implementation Highlights

- **Header**: left (menu/logo), middle (search + voice search), right (create/apps/notifications/avatar) using Flexbox containers. fileciteturn0file0 fileciteturn0file1
- **Sidebar**: fixed, narrow vertical navigation with icon + label and a hover effect. fileciteturn0file0 fileciteturn0file1
- **Video cards**: thumbnail with an absolutely positioned duration label and a two‑column info grid (channel avatar + details). fileciteturn0file0 fileciteturn0file1

## 🛠️ How to Customize

- **Change the grid density**: tweak the media queries in `youtube.css` to set different breakpoints or column counts. fileciteturn0file1
- **Swap content**: replace links, titles, channel names, and view counts directly in `index.html`. fileciteturn0file0
- **Experiment further**: add `gap` to Flexbox containers, try `grid-auto-rows`, or introduce CSS variables for colors/spacing.

## ✅ To‑Do / Future Ideas

- Add a mobile menu toggle for the sidebar
- Implement a search results page or filter chips
- Extract shared styles (variables, utility classes)
- Add basic keyboard navigation for header icons/tooltips

## 📄 License

This is a practice project. Use it freely for learning and portfolio purposes.
