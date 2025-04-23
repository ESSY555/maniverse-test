
# 💅 Mini Nail Design Interface – Maniverse Internship Task

This is my submission for the **Frontend Developer Internship at Maniverse**. It's a fully functional mini nail customization interface built with **React**, featuring nail shape and color selection along with options to save, view, edit, and delete designs.

## 🌐 Live Demo

[🔗 View Live Demo](https://maniverse-test.vercel.app/)

## 📂 GitHub Repository

[📁 View Source Code on GitHub](https://github.com/ESSY555/maniverse-test)

---

## 🛠️ Getting Started Locally

1. **Clone this repo**  
   ```bash
   git clone https://github.com/ESSY555/maniverse-test.git
   ```

2. **Navigate to the folder**  
   ```bash
   cd maniverse-test
   ```

3. **Install dependencies**  
   ```bash
   npm install
   ```

4. **Start the development server**  
   ```bash
   npm start
   ```

The app will run on `http://localhost:3000`.


## 🎯 Features

- ✅ Select a **nail shape** (Almond, Stiletto, Square)
- ✅ Pick a **nail color or pattern**
- ✅ **Live preview** on a mock hand
- ✅ **Summary screen** of the chosen shape and color
- ✅ **Save** customized designs
- ✅ **View** all saved designs
- ✅ **Edit** saved designs
- ✅ **Delete** designs from localStorage

### 🌟 Bonus Features
- ✨ Smooth **animations** during design changes
- 🌀 **Loader** displayed while preview updates
- 💾 Uses **localStorage** to temporarily store designs
- 🧩 Clean and **reusable component structure**

---

## 🧠 Thought Process

The app is structured into modular components:
- `ShapeSelector`
- `ColorSwatch`
- `HandPreview`
- `SummaryScreen`
- `SavedDesigns`

React Hooks (`useState`, `useEffect`) were used for state management. Design changes are stored in localStorage, and animations improve user interaction. Emphasis was placed on making the UI intuitive, responsive, and brand-aligned.

---

## 💡 Assumptions & Limitations

- Patterns are limited to solid colors for simplicity
- LocalStorage is used for demo purposes; no backend or authentication
- The preview hand is a placeholder image; can be replaced with SVG or emoji

---

## 🚀 Future Improvements

- Add **naming** for saved designs
- Support **pattern textures or gradients**
- Connect to a **backend** for persistent saving and user accounts
- Improve **accessibility** (ARIA attributes, keyboard navigation)
- Add **unit tests** for better coverage

---

## 👩‍🎨 UI & Branding

The interface is **fun**, **clean**, and **feminine**, aligning with Maniverse's beauty-tech brand. The layout is built **mobile-first** and is fully responsive across devices.

---

Thank you for the opportunity! I had a lot of fun building this and would love to be part of **Maniverse** to continue crafting beautiful, user-centered digital experiences. 💖

---

