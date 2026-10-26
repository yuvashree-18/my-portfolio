# Yuvashree G — Professional Portfolio Website

> **Aspiring IT Infrastructure, Networking & Cloud Engineer**  
> 🌐 **Live Website:** [https://yuvashree-18.github.io/my-portfolio/](https://yuvashree-18.github.io/my-portfolio/)  
> Location: Chennai, Tamil Nadu  
> Contact: [yuvashreeg18@gmail.com](mailto:yuvashreeg18@gmail.com)  
> LinkedIn: [linkedin.com/in/yuvashree-g-256659372](https://linkedin.com/in/yuvashree-g-256659372)  
> GitHub: [github.com/yuvashree-18](https://github.com/yuvashree-18)

---

## 📁 Project Structure

```text
d:\web test\
│
├── index.html                  # Semantic HTML5 single-page portfolio
├── css/
│   └── style.css               # Dark/light theme, gradients, keyframes, scroll-reveal animations
├── js/
│   └── main.js                 # Theme toggler, scroll animations, stats counters, modals, filters
├── assets/
│   ├── profile-avatar.svg      # Professional high-tech profile avatar
│   ├── Yuvashree_G_Resume.pdf  # Downloadable resume PDF
│   ├── Yuvashree_G_Resume.html # Printable A4-formatted ATS resume
│   └── projects/               # High-fidelity project interface screenshots (SVGs)
│       ├── tvk-mobile.svg      # TVK Perambur Branch Mobile App Mockup
│       ├── food-donation.svg   # Sustainable Food Redistribution & AI Tracker
│       ├── legal-analyzer.svg  # AI Legal Document Analyzer Interface
│       ├── grocery-store.svg   # Grocery Store Storefront & Cart Mockup
│       ├── tindog.svg          # TinDog Landing Page Mockup
│       └── dice-game.svg       # Roll Challenge Game Interface Mockup
├── .gitignore                  # Git ignore rules for clean repo
└── README.md                   # Documentation & deployment guide
```

---

## 🚀 How to Preview on Windows

### Option 1: Direct Browser Launch (No terminal required)
1. Open **File Explorer** and navigate to `d:\web test`.
2. Double-click **`index.html`** to open it directly in your web browser.

### Option 2: PowerShell Start Command
```powershell
Start-Process "d:\web test\index.html"
```

---

## 🌐 How to Publish Online with GitHub Pages

Follow these simple steps to deploy your portfolio live for recruiters:

### Step 1: Create a Repository on GitHub
1. Go to [github.com/new](https://github.com/new) and log in to your account (`yuvashree-18`).
2. Set **Repository name** to:
   - `portfolio` (will be hosted at `https://yuvashree-18.github.io/portfolio/`)
   - OR `yuvashree-18.github.io` (will be hosted at `https://yuvashree-18.github.io/`)
3. Set visibility to **Public**.
4. Leave "Add a README file" unchecked (you already have this one).
5. Click **Create repository**.

### Step 2: Push Your Code to GitHub (Run in PowerShell / Git Bash)
Open your terminal in `d:\web test` and run:

```powershell
cd "d:\web test"
git init
git add .
git commit -m "feat: complete professional portfolio with animations, screenshots and resume"
git branch -M main
git remote add origin https://github.com/yuvashree-18/my-portfolio.git
git push -u origin main
```
*(If prompted, authenticate using your GitHub browser prompt or Personal Access Token).*

### Step 3: Enable GitHub Pages
1. On GitHub, navigate to your repository `my-portfolio`.
2. Click **Settings** (top navigation tab) &rarr; **Pages** (in the left sidebar under "Code and automation").
3. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` and folder `/ (root)`.
4. Click **Save**.
5. Within 1 to 2 minutes, GitHub Pages will deploy your site and display the live URL:
   `https://yuvashree-18.github.io/my-portfolio/`

---

## ✨ Professional Enhancements Added

1. **Profile Photo / Avatar System:**
   - Dedicated glowing avatar ring in the Hero section with live "Available for Opportunities" status pill.
   - Profile Spotlight Card in the About Me section with key credentials.
2. **Animated Stats Counters:**
   - Smooth counting animations on scroll:
     - `8.82` Academic CGPA
     - `12+` Network Protocols
     - `14+` Red Hat Linux Services
     - `6+` Technical Projects
3. **High-Fidelity Project Screenshots:**
   - Replaced all placeholders with 6 dedicated, vector-crisp interface screenshots in `assets/projects/`.
   - Modal viewer displays full mockup graphics upon clicking "View Details & Mockup".
4. **Downloadable Resume:**
   - Direct download button for `assets/Yuvashree_G_Resume.pdf`.
   - Dedicated printable A4 resume view at `assets/Yuvashree_G_Resume.html`.
5. **Smooth Scroll & Micro-Animations:**
   - IntersectionObserver scroll reveal animations (`.reveal`) with staggered entry delays.
   - Card lift and colored glow effects on hover.
