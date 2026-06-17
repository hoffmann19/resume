# Interactive Resume Project

This repository contains the source code for Dan Hoffmann's interactive web-based resume, optimized for both desktop/mobile screens and high-quality PDF printing.

## 🔗 Live Site
Your resume is hosted live on the web at:
👉 **[https://hoffmann19.github.io/resume/](https://hoffmann19.github.io/resume/)**

---

## 📂 Repository Contents
* **`index.html`** / **`resume.html`**: The primary resume file in the **Minimalist Editorial** layout.
  * Defaults to a premium **Midnight Navy & Amber Gold** dark theme.
  * Contains a **Light/Dark Mode** switcher.
  * Contains a **Skim View / Deep Dive** toggle that collapses tactical bullets to show an executive-level summary.
  * Masked email and phone number to protect against scraper bots.
* **`original_resume.html`**: The original two-column layout with the indigo/teal color palette.
* **`resume_terminal.html`**: A fun alternative layout featuring a retro command-line console where recruiters can type active commands (like `help`, `experience`, `skills`) to interact with your resume.
* **`.gitignore`**: Excludes system files (like `.DS_Store`) from Git tracking.

---

## 🛠 How to Make Updates

### 1. Locally Editing Content
1. Open the project folder `/Users/hoffmann19/resume` in your editor (e.g., VS Code).
2. Edit **`resume.html`** directly to update bullet points, dates, or skills.
3. Save the file.

### 2. Pushing Updates Live
When you make an edit to `resume.html`, copy it to `index.html` (the landing page served by GitHub) and push it to GitHub using these terminal commands:
```bash
# Copy local changes to the landing page
cp resume.html index.html

# Stage and commit your changes
git add resume.html index.html
git commit -m "Update resume details"

# Push live to your GitHub Pages website
git push
```

### 3. Printing/Saving as PDF
1. Open the website or local `resume.html` in your browser.
2. Select your desired view (e.g., click **Skim View** if you want a one-page printout, or keep **Deep Dive** for a full-length printout).
3. Click the **"Print or Save PDF"** button (or press `Cmd + P`).
4. Choose **Save as PDF** in your browser's print destination. 
*Note: The print styles automatically format the page to a clean black-and-white print layout, hiding the web buttons and tags.*

---

*This project was created and polished in collaboration with Antigravity (AI Pair Programmer).*
