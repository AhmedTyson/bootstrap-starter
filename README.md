# <img src="https://api.iconify.design/lucide:bootstrap.svg?color=%238A2BE2" width="32" height="32" align="center" /> Bootstrap Starter

> **A Bootstrap 5 static storefront template.**
> Precision-built for ceramics merchandising, practicing rapid UI scaffolding using Bootstrap's responsive grid.

<div align="center">

| Project Status | Type                                                                                   | Framework                                                                                                      | Core Focus        |
| :------------- | :------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------- | :---------------- |
| `STABLE`       | ![Static Site](https://img.shields.io/badge/Type-Template-lightgrey?style=flat-square) | ![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white) | `Responsive Grid` |

</div>

---

## <img src="https://api.iconify.design/lucide:list.svg?color=%238A2BE2" width="20" height="20" align="center" /> Table of Contents

- [Overview](#overview)
- [Pages](#-pages)
- [Tech Stack](#-tech-stack)
- [Bootstrap Components Used](#-bootstrap-components-used)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)

---

## Overview

This project is a Bootstrap 5-powered storefront template built around a ceramic art brand. The goal was to practice rapid UI scaffolding using Bootstrap's grid system, prebuilt components, and utility classes — without writing custom layout CSS from scratch.

The site demonstrates how Bootstrap can be used to construct a professional-looking multi-page e-commerce surface, including product grids, navigation, cards, and responsive breakpoints. It serves as both a learning exercise and a reusable starter template for Bootstrap-based projects.

---

---

## <img src="https://api.iconify.design/lucide:file-text.svg?color=%238A2BE2" width="20" height="20" align="center" /> Pages

| Page                 | File                          | Description                              |
| -------------------- | ----------------------------- | ---------------------------------------- |
| **Home**             | `index.html`                  | Main landing page with featured ceramics |
| **Products**         | `products.html`               | Full product catalog with grid layout    |
| **Ceramic Products** | `products-cera.html`          | Dedicated ceramics category page         |
| **Index (Products)** | `index-products-ceramic.html` | Alternative product index view           |
| **Docs**             | `docs/`                       | Documentation pages                      |

---

---

## <img src="https://api.iconify.design/lucide:cpu.svg?color=%238A2BE2" width="20" height="20" align="center" /> Tech Stack

| Layer            | Technology                            |
| ---------------- | ------------------------------------- |
| **Structure**    | HTML5                                 |
| **Framework**    | Bootstrap 5.3 (via CDN)               |
| **Styling**      | CSS3 + Bootstrap utility classes      |
| **Layout**       | Bootstrap Grid System, Flexbox        |
| **Dependencies** | Bootstrap (CDN — no install required) |

---

---

## <img src="https://api.iconify.design/lucide:component.svg?color=%238A2BE2" width="20" height="20" align="center" /> Bootstrap Components Used

| Component       | Usage                                             |
| --------------- | ------------------------------------------------- |
| **Navbar**      | Responsive top navigation with brand and links    |
| **Cards**       | Product listing cards with images and CTAs        |
| **Grid System** | 3-column responsive product grid                  |
| **Buttons**     | Call-to-action buttons with Bootstrap styling     |
| **Badges**      | Product category and status labels                |
| **Pagination**  | Navigation between product pages                  |
| **Utilities**   | Spacing, typography, color, and display utilities |

---

---

## <img src="https://api.iconify.design/lucide:folder-tree.svg?color=%238A2BE2" width="20" height="20" align="center" /> Project Structure

```
bootstrap-starter/
├── index.html                         # Main landing page
├── products.html                      # Product catalog (all categories)
├── products-cera.html                 # Ceramics product category
├── index-products-ceramic.html        # Ceramics index view
│
├── css/                               # Custom CSS overrides
│   └── style.css
│
└── docs/                              # Documentation HTML pages
    └── docs-html/
```

---

---

## <img src="https://api.iconify.design/lucide:rocket.svg?color=%238A2BE2" width="20" height="20" align="center" /> Getting Started

```bash
# Clone the repository
git clone https://github.com/AhmedTyson/bootstrap-starter.git

# Navigate to the directory
cd bootstrap-starter

# Open in browser
start index.html
```

> Bootstrap is loaded from CDN — no npm install or build step required.
