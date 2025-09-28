# WhatsApp DualPic Chrome Extension (Prototype)

## Overview  
WhatsApp DualPic is a Chrome Extension prototype that redefines how users express themselves on WhatsApp Web.  
The extension allows uploading two profile pictures and assigning selective visibility rules (e.g., Family, Friends, Work).  

This solves a long-standing UX gap: users want to show different sides of themselves—professional vs. personal—without compromising privacy.

---

## Live Demo  
🎥 [ X (Twitter) Demo]([https://twitter.com/yourdemo](https://x.com/JusticePlange/status/1917779218467021129)  
💻 [GitHub Repository](https://github.com/JayPlange/WhatsAppDualpic)

---

## Features (Current Prototype)  
✅ Dual Profile Picture: Upload and switch between two images.  
✅ Selective Visibility: Assign who sees which image (proof-of-concept).  
✅ User-Friendly UI: Clean React + Tailwind interface for setup.  
✅ Secure Handling: Local-only storage of images/settings (no external servers).  

---

## Roadmap (Next Iterations)  
- [ ] Multi-profile support (more than 2 images).  
- [ ] Advanced rules editor (group-level, contact-level).  
- [ ] Cross-browser support (Firefox, Edge).  
- [ ] Automated testing with Cypress.  
- [ ] Performance optimization for large contact lists.  

---

## Project Structure  
- `src/` – Core extension logic (React + TypeScript).  
- `mobile/` – Assets and mobile-related adjustments.  
- `WhatsAppDualPic/` – Main Chrome extension folder.  
- Configs – `tailwind.config.js`, `.env`, `tsconfig.*.json` for environment & build.  

---

## Tech Stack  
- React + TypeScript → Strongly-typed, modular frontend.  
- TailwindCSS + PostCSS → Rapid, consistent styling.  
- Vite → Lightning-fast development & optimized builds.  
- Chrome Extension APIs → DOM injection & event handling.  

---

## Installation & Setup  
```bash
# Clone repo
git clone https://github.com/JayPlange/WhatsAppDualpic.git

# Move into project folder
cd WhatsAppDualpic

# Install dependencies
npm install

# Run dev server
npm run dev
