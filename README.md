# Mass Responses

**Mass Responses** is a lightweight, open-source project for presenting Catholic liturgical texts — especially **Mass responses** — in a clean, distraction-free, and multilingual format.

The goal is to make it easy for anyone (travelers, parishioners, homeschoolers, catechists, or the simply curious) to:

* follow the Mass in multiple languages
* compare translations side by side
* access texts quickly on mobile or desktop
* contribute improvements over time

This project is intentionally simple, static, and transparent.

---

## ✨ Features

* 🌍 **Multiple languages** with fast switching
* 📖 **Side-by-side comparison** of translations
* 📱 **Mobile-friendly** layout
* ⚡ **Static site** built with Astro (fast, secure, low-cost to host)
* 🧩 Translation files stored as structured JSON
* 🔓 Fully **open source**

---

## 🏗️ Tech Stack

* [Astro](https://astro.build/) — static site framework
* Vanilla JavaScript + CSS
* JSON-based translation files
* Designed for deployment on Cloudflare Pages

---

## 📁 Project Structure (simplified)

```
mass-responses/
├─ src/
│  ├─ pages/
│  ├─ components/
│  └─ translations/
│     └─ full/          # Ignored (local / frozen translations)
├─ public/
├─ astro.config.mjs
├─ package.json
└─ README.md
```

> ⚠️ Note: Files in `src/translations/full/` are intentionally **ignored by Git**.
> They are meant for local, complete, or frozen translations and should not be required at runtime.

---

## 🚀 Local Development

### Install dependencies

```bash
npm install
```

### Run dev server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

The static output will be generated in `dist/`.

---

## 🌐 Deployment

This project is designed to deploy cleanly on **Cloudflare Pages**:

* Build command: `npm run build`
* Output directory: `dist`
* No server-side code required

---

## 🤝 Contributing

Contributions are welcome, especially for:

* new translations
* corrections or clarifications
* UX improvements
* accessibility improvements

If you plan to contribute translations:

* please place **canonical/shared** translations in tracked folders
* avoid committing full or frozen personal copies

Open an issue or pull request to start a discussion.

---

## 📜 License

This project is open source and released under the **MIT License**.

---

## 🙏 Intent

This project is offered freely, in the spirit of service.

If it helps you pray, learn, or participate more fully in the liturgy — that is its purpose.

If you would like to donate, you can do so here: https://buymeacoffee.com/mikebebs :)
