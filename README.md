
# 📖 Manga Reader

Welcome to **Manga Reader**, a sleek and modern web-based manga reading platform inspired by **Manga Plus**. Designed with responsiveness and user experience in mind, this project offers a clean and intuitive interface for reading your favorite manga titles. Built with **Tailwind CSS** and the **Roboto** font, it includes essential features like a search bar, chapter navigation, favorites, and user authentication forms.

> ⚠️ **Disclaimer:** This is a student/developer project and not intended for commercial use without proper licensing for content.

---

## 🌟 Features

- ✅ **Responsive Design**: Adapts beautifully across desktop, tablet, and mobile (1–4 column grid).
- 🔍 **Live Search**: Filter manga titles in real-time with the active search bar.
- 📚 **Manga Reader**: Full-screen mode, zoom controls, and Prev/Next chapter navigation.
- 📄 **Manga Details Page**: Displays manga cover, description, and all chapters.
- ⭐ **Favorites System**: Save manga with localStorage for personalized reading.
- 🔐 **Login/Sign-Up Pages**: Simulated user authentication, extendable via backend.
- 📘 **About Page**: Learn about the platform and its purpose.
- 🎴 **Preloaded Manga Titles**: Jujutsu Kaisen, One Piece, Blue Lock, Solo Leveling (*user-provided*).

---

## 🚀 Live Demo

🔗 [**View Live Demo**](https://manga-reader-sage.vercel.app/)

---

## 🛠️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/manga-reader.git
cd manga-reader
````

### 2️⃣ Run Locally

As a static website, use a local HTTP server:

```bash
npm install -g live-server
live-server
```

🔁 Or simply open `index.html` in your browser (some features may not work due to CORS).

---

## 🔗 Dependencies

* 📦 No build tools needed!
* 🧵 Tailwind CSS via CDN
* 🖋️ Google Fonts (Roboto)

Ensure an active internet connection to load external resources.

---

## 👇 Usage Guide

### 🏠 **Home Page (`index.html`)**

* Browse a grid of manga.
* Use the search bar to filter.
* Click **"Read Free"** or the title to view more.

### 📖 **Reader**

* Navigate chapters and pages using `Prev` / `Next`.
* Use `Zoom In/Out` and `Full Screen` for better viewing.

### ⭐ **Favorites (`favorites.html`)**

* Click the ☆ or ★ icon to add/remove from favorites.
* View saved manga anytime.

### 🔐 **Login/Sign-Up (`login.html` / `signup.html`)**

* Simulated login forms.
* Extend using a backend like Firebase or Express.js.

### 🧾 **Manga Details (`details.html?manga=ID`)**

* Shows manga cover, description, and chapters.
* Linked from home and favorites.

### 💬 **About Page (`about.html`)**

* Learn more about the purpose and structure of Manga Reader.

---

## 🗂️ Project Structure

```
manga-reader/
├── index.html        # Home page
├── details.html      # Manga details view
├── favorites.html    # User's favorites
├── about.html        # Info/about section
├── login.html        # Login form
├── signup.html       # Sign-up form
└── README.md         # You're here!
```

---

## 🖼️ Manga Content

**Included Titles:**

* Jujutsu Kaisen
* One Piece
* Blue Lock
* Solo Leveling

**Sources:**

* Covers/pages pulled from Amazon, Pinterest, CBR (for demo purposes).

> ⚠️ **Copyright Warning**
>
> These titles are copyrighted by their publishers (e.g., Shueisha, Kodansha).
> For production or public deployment, replace with:
>
> ✅ **Public Domain Manga**: e.g., *"Say Hello to Black Jack"* by Shuho Sato
> 🆓 **Royalty-Free Images**: Use sites like [Pixabay](https://pixabay.com/) or [Unsplash](https://unsplash.com/)
> 📡 **Legal APIs**: Integrate with [MangaDex](https://mangadex.org/) for open-access manga

---

## 🛠️ Customization Tips

* ➕ **Add Manga**: Edit `mangaData[]` in the `<script>` of each HTML file.
* 🔧 **Backend Auth**: Integrate Firebase or Node.js to enable real login.
* 🔍 **Enhanced Filters**: Filter manga by genre, author, or status.
* 💬 **Comments & Ratings**: Connect to a database (e.g., Firebase Realtime DB).
* 📡 **API Support**: Use MangaDex or other legal APIs to fetch manga dynamically.

---

## 👥 Contributing

We welcome contributions! 💖

1. Fork the repository
2. Create a new branch
   `git checkout -b feature-xyz`
3. Commit your changes
   `git commit -m "Added feature xyz"`
4. Push the branch
   `git push origin feature-xyz`
5. Open a Pull Request 🚀

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
You’re free to use, modify, and distribute it. Be mindful of third-party content usage.

---

## 🙏 Acknowledgments

* 👓 Inspired by Manga Plus
* 🎨 Styled with Tailwind CSS
* 🖋️ Fonts by Google Fonts (Roboto)
* 🖼️ Icons and assets from Pixabay

