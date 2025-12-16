# 🌍 World Exams

> **Free practice exams for standardized tests worldwide**

[![Active](https://img.shields.io/badge/status-active-brightgreen)](https://world-exams.github.io)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Open Source](https://img.shields.io/badge/open-source-orange.svg)](https://github.com/world-exams)

## 🎯 Mission

Democratize access to quality exam preparation materials for standardized tests around the world. Every student deserves free access to practice questions and study resources.

## 🗺️ Available Platforms

### ✅ Active

- **🇨🇴 Colombia** - [Saber Para Todos](https://saberparatodos.space) - Saber 11° ICFES

### 🚧 Coming Soon

- **🇲🇽 México** - EXANI-II / CENEVAL
- **🇧🇷 Brasil** - ENEM
- **🇦🇷 Argentina** - Ingreso Universitario
- **🇨🇱 Chile** - PAES
- **🇵🇪 Perú** - Admisión Universitaria
- **🇺🇸 USA** - SAT
- **🇨🇳 China** - Gaokao (高考)
- **🇮🇳 India** - JEE Main

## 🏗️ Architecture

Each country has its own repository with:

- **Public UI** - Astro + Svelte components
- **Country-specific content** - Localized to the target audience
- **Shared API** - Centralized question bank (private backend)

### Structure

```
world-exams/
├── world-exams.github.io     # Landing page (this repo)
├── saber-co                  # Colombia UI
├── exani-mx                  # México UI
├── enem-br                   # Brasil UI
└── [other countries]         # More to come...

Backend (Private):
└── saberparatodos            # API + Questions + Edge Functions
```

## 🤝 Contributing

We welcome contributions! Each country platform accepts:

- 📝 New practice questions
- 🐛 Bug reports
- 🌟 Feature requests
- 🌐 Translations
- 🎨 UI/UX improvements

See individual repository READMEs for specific contribution guidelines.

## 🛠️ Tech Stack

- **Frontend**: Astro 5 + Svelte 5 + TailwindCSS
- **Backend**: Cloudflare Pages + Workers
- **Database**: Supabase (PostgreSQL + Edge Functions)
- **AI**: Gemini API for content generation
- **Hosting**: Cloudflare Pages (free tier)

## 📄 License

MIT License - See [LICENSE](LICENSE) for details.

Question content varies by source:
- Original questions: CC BY-SA 4.0
- AI-generated variations: CC BY-NC-SA 4.0

## 🌟 Star History

If you find this project useful, please consider giving it a ⭐️

## 📞 Contact

- **Organization**: [github.com/world-exams](https://github.com/world-exams)
- **Website**: [world-exams.github.io](https://world-exams.github.io)

---

**Made with ❤️ by the open source community**
