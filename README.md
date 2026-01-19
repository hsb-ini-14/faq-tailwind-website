# FAQ Tailwind Website

An interactive and responsive **FAQ (Frequently Asked Questions) Website** built with **React, Vite, and Tailwind CSS**.
This project features smooth accordion animations, dark mode support, and an elegant UI for browsing common questions.

🔗 **Live Demo:** [https://hsb-ini-14.github.io/faq-tailwind-website/](https://hsb-ini-14.github.io/faq-tailwind-website/)

---

## ✨ Features

* 📂 Accordion-style expandable FAQ items
* 🔁 Expand All / Collapse All functionality
* 🌙 Light / Dark mode toggle (with persistence)
* 🎞️ Smooth height & opacity transitions
* 📱 Fully responsive layout
* 🎨 Styled with Tailwind CSS v4
* ⚡ Built using Vite for fast development

---

## 🛠️ Tech Stack

* **React** – UI components & state management
* **Vite** – Fast build tool & dev server
* **Tailwind CSS** – Utility-first styling
* **Boxicons** – Icon set (for expand/collapse & theme toggle)
* **GitHub Pages** – Deployment

---

## 📁 Project Structure

```text
faq-tailwind-website/
├── public/
├── src/
│   ├── components/
│   │   ├── FAQItem.jsx
│   │   └── FAQList.jsx
│   ├── data/
│   │   └── faqData.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── vite.config.js
├── package.json
├── package-lock.json
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1️⃣ Clone the repository

```bash
git clone https://github.com/hsb-ini-14/faq-tailwind-website.git
cd faq-tailwind-website
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Start the development server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## 🌍 Deployment to GitHub Pages

This project is deployed using **gh-pages**.

### Steps used:

1. Install gh-pages

```bash
npm install --save-dev gh-pages
```

2. Set base path in `vite.config.js`

```js
export default defineConfig({
  base: "/faq-tailwind-website/",
});
```

3. Add scripts to `package.json`

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```

4. Deploy

```bash
npm run deploy
```

---

## 🧩 How It Works

* FAQ content is stored in a central `faqData.js` file
* Each FAQ item is rendered using the reusable `FAQItem` component
* `FAQList` manages open/close state and Expand All logic
* React `useState` tracks:

  * Currently opened FAQ item
  * Expand All mode
  * Dark mode toggle
* Dark mode preference is saved to `localStorage`
* Tailwind utility classes handle animations, layout, and theming

---

## 📸 Preview

> to be added later

---

## 🙌 Acknowledgements

* Icons by [Boxicons](https://boxicons.com/)
* Styling powered by [Tailwind CSS](https://tailwindcss.com/)
* Build tool by [Vite](https://vitejs.dev/)

---

## 👤 Author

**Harsh Singh Bhaduria**

* GitHub: [https://github.com/hsb-ini-14](https://github.com/hsb-ini-14)

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub — it really helps! 😊
