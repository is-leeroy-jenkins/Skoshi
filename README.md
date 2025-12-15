

# 🎨 Skoshi

**Skoshi** is a clean, minimalist Flask-based portfolio application designed to showcase projects, skills, and professional identity with clarity and restraint.
It emphasizes **simplicity, readability, and classical web fundamentals**—HTML, CSS, and Python—without unnecessary framework bloat.

Skoshi is intentionally small (“skoshi”) in footprint, but deliberate in design.



## ✨ Features

* **Flask-powered backend** with clean routing and template rendering
* **Responsive, modern UI** driven by handcrafted CSS
* **Base template architecture** for consistent layout and extensibility
* **Portfolio-first design** focused on content, not distractions
* **Production-ready structure** suitable for personal sites or small professional showcases



## 🧱 Project Structure

```
skoshi/
│
├── app.py              # Flask application entry point
├── requirements.txt    # Python dependencies
│
├── templates/
│   ├── base.html       # Global layout and shared structure
│   └── index.html      # Landing / portfolio page
│
└── static/
    └── main.css        # Core styling and layout rules
```

This structure follows established Flask conventions and keeps concerns cleanly separated:

* **Python** handles routing and logic
* **HTML templates** define structure and semantics
* **CSS** controls presentation with no inline coupling



## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/skoshi.git
cd skoshi
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv .venv
source .venv/bin/activate      # macOS / Linux
.venv\Scripts\activate         # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

By default, the app will be available at:

```
http://127.0.0.1:5000
```



## 🖥️ Application Overview

### `app.py`

* Initializes the Flask application
* Defines primary routes
* Serves the portfolio landing page

The design favors **explicitness over magic**—routes are easy to read and modify.

---

### `base.html`

* Defines the global HTML layout
* Centralizes navigation, metadata, and styling hooks
* Enables consistent page composition through template inheritance

This keeps future expansion clean and predictable.

---

### `index.html`

* Primary portfolio landing page
* Designed for clarity, scannability, and professional presentation
* Ideal for:

  * Personal branding
  * Resume-adjacent content
  * Project highlights

---

### `main.css`

* Custom styling with no CSS framework dependencies
* Emphasizes:

  * Typography
  * Whitespace
  * Visual hierarchy
* Easily extensible for themes or dark-mode variants


## 🎯 Design Philosophy

Skoshi is built around a few core principles:

* **Minimalism beats novelty**
* **Readable code is maintainable code**
* **Small, intentional systems age better than large abstractions**
* **A portfolio should highlight *work*, not the framework**

This makes Skoshi ideal for engineers, analysts, and technologists who value substance over flash.



## 🔧 Customization Ideas

* Add additional routes for:

  * `/projects`
  * `/about`
  * `/contact`
* Integrate Flask-WTF for forms
* Add Markdown rendering for blog-style content
* Deploy using:

  * Gunicorn + Nginx
  * Docker
  * Fly.io / Render / Railway



## 📦 Dependencies

Key dependencies include:

* `Flask` – Core web framework
* `Flask-Bootstrap` – Optional UI helpers
* `Flask-WTF` – Form handling
* `Flask-Login` – Authentication support
* `Markdown` & `bleach` – Safe content rendering

All dependencies are explicitly declared in `requirements.txt`.



## 🪪 License

This project is provided for personal and professional use.
You are free to fork, adapt, and extend it for your own portfolio or learning purposes.



## 👋 Closing Note

Skoshi is intentionally modest—but carefully built.
It reflects a belief that **clean structure, timeless patterns, and disciplined scope** are what make software endure.

If you want a portfolio that feels *engineered*, not assembled—Skoshi is a solid foundation.



If you’d like, I can also:

* Add **screenshots / preview sections**
* Create a **GitHub Pages–style demo**
* Introduce **dark mode**
* Rewrite this README with a more playful or more corporate tone

Just say the word.
