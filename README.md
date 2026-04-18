# Study Perth Assistant

A comprehensive full-stack web application designed to empower students in Perth with educational resource management, community Q&A, and streamlined communication tools.

---

## 👥 Project Context & My Role
This was a **collaborative team project** focused on building a scalable community platform. While the project was a team effort, I was responsible for the following core areas:

* **Designed the complete UI/UX system and led frontend development. Additionally, performed extensive technical debugging to resolve layout inconsistencies and cross-browser compatibility issues, ensuring a polished and stable final product.

---

## 🚀 Key Features

### 🔐 User Security & Management
* **Full Auth Cycle:** Secure registration, login, and profile management.
* **Verification:** Email verification and password recovery powered by AWS/SMTP integration.
* **Profile Customization:** Support for secure file uploads (avatars) and profile metadata.

### 💬 Community Engagement (Q&A)
* **Interactive Platform:** Users can post, edit, and delete questions and answers.
* **Social Dynamics:** Like/dislike system for community-driven content ranking.
* **Rich Text Support:** Integrated CKEditor for professional content formatting.

### 🔍 Discovery & UX
* **Global Search:** Advanced search functionality across all user-generated content.
* **Optimized Performance:** Paginated content loading and CDN-backed resource delivery.
* **Responsive UI:** Sleek, modern design utilizing the Inter typeface and FontAwesome icons.

---

## 🛠 Technical Stack

- **Backend:** Flask (Python), Flask-Login, Flask-Mail
- **Frontend:** Jinja2, Bootstrap 5, JavaScript, CSS3
- **Database:** SQLAlchemy ORM, SQLite/PostgreSQL
- **Infrastructure:** AWS SES (Email), Werkzeug (Security), Flask-WTF (Form Validation)

---

## 📂 Project Structure Highlights
The application follows a modular **Blueprint-like** structure for maintainability:
- `app/question/`: Logic for the Q&A engine.
- `app/user/`: User lifecycle and authentication logic.
- `app/static/`: Organized assets (CSS/JS/Uploads).
- `app/templates/`: Highly modular Jinja2 template inheritance.

---

## 🛠 Installation & Setup

1. **Clone & Navigate:**
   ```bash
   git clone [https://github.com/Rebecca115/](https://github.com/Rebecca115/)[Repo-Name].git
   cd [Repo-Name]
