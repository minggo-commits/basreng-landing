# 🌶️ Basreng Pedas Daun Jeruk - Premium Landing Page Template

> [!NOTE]  
> This premium template was meticulously crafted using **Antigravity** powered by **Gemini 3 Flash** for maximum speed, SEO efficiency, and modern design standards.

A high-converting, professional, and SEO-optimized landing page template built with **Astro** and **Tailwind CSS**. Designed specifically for snack products with a focus on vibrant aesthetics and clear call-to-actions.

---

## 🚀 Quick Start

### 1. Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed (LTS version recommended).

### 2. Installation
Clone or download the project, then run:
```bash
npm install
```

### 3. Development
Start the local development server:
```bash
npm run dev
```
Open [http://localhost:4321](http://localhost:4321) to view the site in your browser.

---

## 🛠️ Customization Guide

### How to Add/Edit Products
All product variants are managed in `src/pages/index.astro`. Locate the `variants` array in the frontmatter:

```typescript
const variants = [
    {
        name: "Nama Produk",
        description: "Deskripsi singkat.",
        price: "Rp 00.000",
        image: "/images/your-image.png",
        tag: "Best Seller"
    },
    // Add more here...
];
```

### How to Add Images
1.  Place your image files in the `public/images/` directory.
2.  Reference them in your code using the path starting from root, e.g., `/images/my-new-basreng.png`.

> [!TIP]
> Use `.webp` format for better performance and smaller file sizes.

### How to Update WhatsApp Link
Change the `whatsappNumber` variable in `src/pages/index.astro`:
```typescript
const whatsappNumber = "6281234567890"; // Use international format without '+'
```

---

## 📈 SEO & Performance

### Dynamic Metadata
To update the page title or meta description for SEO, edit the `<Layout>` component in `src/pages/index.astro`:
```astro
<Layout 
    title="Judul SEO Anda" 
    description="Deskripsi menarik untuk Google search results."
>
```

### Performance Features
-   **Lazy Loading**: Images are automatically lazy-loaded (except for the Hero section) to ensure fast initial page speed.
-   **Astro Islands**: Zero-JavaScript by default, ensuring lightning-fast interaction.
-   **Google Fonts Optimization**: Pre-connected and loaded efficiently.

---

## 🏗️ Folder Structure
```text
├── public/                 # Static assets
│   └── images/             # Product and hero images
├── src/
│   ├── layouts/            # Base templates (SEO, Meta tags)
│   ├── pages/              # Routing (index.astro is the main page)
│   └── styles/             # Global CSS & Tailwind configuration
├── astro.config.mjs        # Astro configuration
└── tailwind.config.mjs     # Tailwind CSS configuration
```

---

## � GitHub SEO Optimization (Recommended)
To make this repository easy to find, set the following metadata in your GitHub repository settings:

**Repository Description:**
`🌶️ Premium Landing Page Template for Basreng & Snacks. Built with Astro & Tailwind CSS. SEO-optimized, ultra-fast, and WhatsApp integration ready. Created with Antigravity AI.`

**Repository Topics (Tags):**
`astro`, `tailwindcss`, `landing-page`, `template`, `seo-friendly`, `basreng`, `food-template`, `website-template`, `antigravity-ai`, `gemini-ai`

---

## �📦 Deployment
Build the project for production:
```bash
npm run build
```
The output will be in the `dist/` folder, ready to be hosted on Netlify, Vercel, or any static hosting provider.

---

## 📝 License
Created by **Antigravity AI (Gemini 3 Flash)**. Feel free to use and modify for your business!
