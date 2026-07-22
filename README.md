# Apen Services (`services.apenapps.com`)

A centralized, professional hub for custom software architecture, enterprise engineering, and bespoke digital solutions developed by **Apen Apps**. Built using a strict, shadow-free, modern minimalist design aesthetic with fluid components engineered for seamless client engagement.

---

## 🚀 Tech Stack

*   **Framework:** Next.js (App Router)
*   **Styling:** Tailwind CSS v4
*   **Typography:** Oxanium (Headings), Montserrat (Body)

---

## 🎨 Design System Specifications

The application strictly implements a flat utility system directly coupled with Google-style structural properties:

*   **Primary Accent:** `#3CC68A` (Services Emerald Green)
*   **Secondary Accent:** `#E7B339` (Gold)
*   **Light Theme Background:** `#FFFFFF`
*   **Dark Theme Background:** `#171717` (True Deep Dark Neutral)
*   **Border Radius:** Modern, rounded-container shapes (`rounded-xl` / `rounded-2xl`)
*   **Shadows:** None (`box-shadow: none !important` forced globally)

---

## 📁 Repository Structure

```text
├── app/
│   ├── layout.tsx       # Core root configuration (Fonts optimization & wrappers)
│   ├── page.tsx         # Main dynamic services platform view
│   └── globals.css      # Consolidated centralized CSS & Tailwind configuration
├── components/
│   ├── global/
│   │   ├── Navbar.tsx   # Dual-theme top navigation layout header
│   │   └── Footer.tsx   # Simplified automated copyright block
│   └── home/
│       ├── Header.tsx   # Enterprise marketing introduction engine
│       ├── Filters.tsx  # Service domain client action controls
│       └── ServiceCard.tsx # Unified grid listing container interface
```

## 🛠️ Getting Started
### 1. Installation
Clone the repository and install dependencies:
```npm install```

### 2. Development Server
Run the local compiler pipeline:
```npm run dev```

Open http://localhost:3000 inside your engine to view the development preview.

## 3. Production Compilation

Build and optimize for server runtime execution:
```bash
npm run build
npm run start
```
