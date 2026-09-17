# Marcelo Garcia — Online CV / Portfolio Website

This folder contains the complete, self-contained files for Marcelo Garcia's modern online CV and portfolio.

## Files
- `index.html`: Fully self-contained dark-mode single-page website with Tailwind CSS, Iconify icons, responsive layout, and smooth-scroll sections.
- `MGarcia_CV_Redesigned_2026.docx`: Matching executive Word document.

## How to Publish to GitHub Pages

### Option A: As your main GitHub user site (Recommended)
1. Create a public repository on GitHub named:
   **`marcelodevops.github.io`**
2. In your terminal, run:
   ```bash
   cd ~/Downloads/Marcelo_Garcia_Online_CV
   git init
   git add .
   git commit -m "Initial commit of online CV"
   git branch -M main
   git remote add origin git@github.com:marcelodevops/marcelodevops.github.io.git
   git push -u origin main
   ```
3. Your CV will be live at: **`https://marcelodevops.github.io`**

---

### Option B: Under a project subpath (`/cv`)
1. Create a repository on GitHub named **`cv`**.
2. In your terminal:
   ```bash
   cd ~/Downloads/Marcelo_Garcia_Online_CV
   git init
   git add .
   git commit -m "Initial commit of online CV"
   git branch -M main
   git remote add origin git@github.com:marcelodevops/cv.git
   git push -u origin main
   ```
3. In GitHub repo **Settings** → **Pages**:
   - Set **Source** to **Deploy from a branch** (`main` / root `/`)
4. Your CV will be live at: **`https://marcelodevops.github.io/cv`**
