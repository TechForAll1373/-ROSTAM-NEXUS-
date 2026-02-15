# 🌐 ROSTAM NEXUS Web Interface  💚🤍❤️ 🟢⚪🔴  

The **ROSTAM NEXUS Web Interface** is a powerful, client‑side searchable armory that brings over **200 open‑source tools** to your fingertips.  
Built with pure HTML, CSS, and JavaScript, it requires no backend – just open `index.html` in any modern browser.

---

## ✨ Features  

- **🔍 Real‑time Search** – Filter tools by name, description, or tags.  
- **📂 Category Filters** – Quickly switch between Mobile VPN, Desktop Apps, Messengers, F‑Droid Repos, and more.  
- **📱 Responsive Design** – Works flawlessly on phones, tablets, and desktops.  
- **🎨 Modern Aesthetic** – Dark theme with neon accents, smooth animations, and a clean grid layout.  
- **🔗 One‑Click Links** – Direct access to GitHub releases, Play Store, F‑Droid, and official websites.  
- **📋 Copy Repo URLs** – For F‑Droid repositories, simply click to copy the address.  

---

## 🚀 How to Use  

1. **Open** the `index.html` file in any browser (Chrome, Firefox, Edge, Safari).  
2. **Browse** or **Search** for your desired tool.  
3. **Click** the relevant button:  
   - **GitHub** – takes you to the latest release page.  
   - **Play / App Store** – opens the store listing.  
   - **F‑Droid** – opens the F‑Droid package page.  
   - **Web** – visits the official project website.  
   - **Copy** – for F‑Droid repos, copies the repository URL to your clipboard.  

---

## 🛠️ Developer Notes  

- The entire tool database is stored in a JavaScript array inside `index.html`.  
- To add or update a tool, edit the `database` array following the existing structure.  
- Categories are defined by the `cat` property (e.g., `["mobile", "vpn"]`).  
- Tags (`tags`) are used for search and visual styling.  

Example entry:  
```js
{ name: "ExampleVPN", sub: "Android", desc: "A secure VPN client.", tags: ["VPN", "FOSS"], cat: ["mobile", "vpn"], release: "https://github.com/example/releases", play: "..." }
