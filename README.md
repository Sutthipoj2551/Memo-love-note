# 💕 our-memory — Memory Gallery

A private, romantic photo gallery built with **Vue 3 + Vite + Tailwind CSS v4**.  
All data (photos, titles, couple names) is stored persistently in the browser's **IndexedDB** — nothing is uploaded to any server.

---

## ✨ Features

- 💑 Editable couple names displayed in the hero
- 📷 Unlimited photo uploads via drag & drop or click-to-browse
- 🗂️ Masonry gallery (1–5 columns, fully responsive)
- ✏️ Rename any memory at any time
- 🗑️ Delete with confirmation dialog
- 💾 Persistent storage — survives page refresh, tab close, and browser restart
- 🌸 Floating petal animations, daisy decorations, heartbeat effects
- 📱 Fully responsive: mobile → tablet → desktop

---

## 📁 Project Structure

```
src/
├── main.js                  ← App entry point
├── App.vue                  ← Root component (wires everything)
├── style.css                ← Global styles + Tailwind import
├── db.js                    ← IndexedDB helper functions
├── useGallery.js            ← Composable: all state & logic
└── components/
    ├── PetalBackground.vue  ← Floating petal animation layer
    ├── AppHeader.vue        ← Hero with couple names & stats
    ├── UploadArea.vue       ← Drag & drop upload zone
    ├── GalleryGrid.vue      ← Masonry photo grid + empty state
    ├── PhotoCard.vue        ← Individual memory card
    ├── EditModal.vue        ← Rename a memory
    ├── DeleteModal.vue      ← Delete confirmation
    └── AppFooter.vue        ← "Created with love" footer
```

---

## 🚀 Getting Started

**Requirements:** Node.js `^22.18.0` or `>=24.12.0`

```sh
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Format source code
npm run format
```

---

## 🛠️ Tech Stack

| Tool | Version | Role |
|------|---------|------|
| Vue 3 | ^3.5 | Composition API, components |
| Vite | ^8.0 | Build tool & dev server |
| Tailwind CSS | v4 | Utility-first styling |
| IndexedDB | native | Persistent photo + metadata storage |
| Prettier | 3.8 | Code formatting |

---

*Made with ❤️ — just for the two of you.*
