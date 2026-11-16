<div align="center">

# ✨ SADEEM | سَدِيم

**A message from you, that may reach a stranger.**

🔗 **Live Demo:** [sadeem-5fw.pages.dev](https://sadeem-5fw.pages.dev/)

![Sadeem](screenshots/cover.png)

</div>

---

## 🌌 The Idea

In a world of followers and likes, I wanted a quiet space where it doesn't matter *who* you are, only *what* you say.

**Sadeem** (Arabic for *nebula*) is a shared digital universe. You draw your own star, write a message inside it, and release it into the sky. In return, you discover stars left behind by strangers, each carrying their words.

No name. No account. Just a small trace left in the sky.

---

## ⭐ Features

- ✍️ **Hand-drawn stars** with touch and mouse support
- 💌 **A short message** inside every star
- 🔭 **Explore** stars and messages left by strangers
- 🕶️ **Fully anonymous**, no sign-up required
- ⚡ **Real-time updates** as new stars arrive
- 🎵 **Synthesized ambient sound**, no audio files
- 🛡️ **Content guidelines** and user reporting
- 🌙 **Arabic-first**, responsive design

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | Vanilla JavaScript, HTML, CSS, built with **Vite 6** |
| **Graphics** | **Canvas 2D**: procedural nebula, starfield, glowing hand-drawn sprites |
| **Audio** | **Web Audio API**: fully synthesized, no audio files |
| **Fonts** | Amiri & IBM Plex Sans Arabic (self-hosted via Fontsource) |
| **Database** | **Supabase**: PostgreSQL with Row Level Security & `SECURITY DEFINER` functions |
| **Realtime** | Supabase Realtime for live updates |
| **Auth** | Supabase Auth with **TOTP two-factor** for the admin dashboard |
| **Hosting** | Cloudflare Pages |

---

## 🔒 Security & Testing

Privacy and security are the foundation of Sadeem, not an add-on.

- 🛡️ Strict **Content Security Policy** and security headers
- 🔍 **ESLint** with the `security` and `no-unsanitized` plugins
- 🧪 **258 database tests** with PGlite
- 🔐 Database access locked down with Row Level Security
- 👤 Admin dashboard protected by TOTP two-factor authentication

---

## 📸 Screenshots

| Draw | Write | Discover |
|---|---|---|
| ![Draw](screenshots/draw.png) | ![Write](screenshots/release.png) | ![Discover](screenshots/explore.png) |

---

## 👩‍💻 Developer

**Taif Al Shari**: designed and developed independently, from concept to launch.

[LinkedIn](https://www.linkedin.com/in/taif-al-shari-978aa4322)

---

<div align="center">

*Every star in Sadeem was once a word in someone's heart.* ✨

</div>
