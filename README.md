# 🌐 InnovateHive – Official Website

Live Site: **https://sohamghadge24.github.io/InnovateHive/**

InnovateHive is a modern, responsive, theme-enabled website showcasing services, features, projects, and testimonials using clean UI design and dynamic JavaScript rendering. This project focuses on smooth user experience, mobile responsiveness, and maintainable modular code.

---

## 🚀 Features

### 🌗 Light/Dark Theme System
- CSS custom properties for both themes  
- Smooth transitions (0.3s ease-out)  
- Theme toggle button (🌙 / ☀️)  
- Preference saved in **localStorage (`ih_theme`)**  
- Auto-load theme on page start  

---

## 🏠 Homepage Enhancements
The homepage contains **five fully responsive, animated sections**:

### ✔ Features Section
- 6 feature cards with icons and hover animations  
- Responsive grid (3 → 1 columns)

### ✔ How It Works Section
- 5-step workflow (Discover → Support)  
- Numbered badges with gradient styling  
- Staggered entrance animations  

### ✔ Featured Projects
- 6 project cards rendered from CSV-driven JS array  
- Emoji placeholders (future image support)  
- Hover elevation effects  

### ✔ Testimonials
- 3 client reviews with ratings and avatar badges  
- Clean, readable layout matching theme  

### ✔ Call-to-Action (CTA)
- Gradient background  
- “Get Started” & “Contact Us” buttons  
- Responsive layout for all screen sizes  

---

## 📦 Dynamic Rendering
The website uses structured JavaScript arrays to generate all homepage sections:

- `FEATURES`  
- `PROCESS`  
- `PROJECTS`  
- `TESTIMONIALS`  

Rendering functions:
- `renderFeatures()`  
- `renderProcess()`  
- `renderProjects()`  
- `renderTestimonials()`  

All are executed when navigating to the home page via `navigate("home")`.

---

## 📱 Responsive Design
- Mobile-first layout  
- 1–3 column design depending on screen size  
- Flexible CTA button stacking  
- Optimized spacing and font scaling  

---

## 🎨 Design System
- Color palette: **Teal (#00a885)** & **Coral (#ff6b35)**  
- Typography: **Poppins** (headings), **Inter** (body)  
- Shadow + elevation system for depth  
- Smooth fade/slide animations for section entrances  

---

## 📊 Project Statistics
- **5** new homepage sections  
- **4** data arrays (48 items total)  
- **5** rendering functions  
- **200+** new CSS rules  
- **50+** new JavaScript lines  
- Semantic HTML & AAA-level accessibility  
- No console errors  

---

## 🛠 Installation & Usage

Clone and run locally:

```bash
git clone https://github.com/sohamghadge24/InnovateHive.git
cd InnovateHive
open index.html
