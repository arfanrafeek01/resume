# Arfan Rafeek — Finance Professional Resume Website

A fast, lightweight, and modern resume website built with the [Hugo](https://gohugo.io/) static site generator and the minimalist [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. The site is automatically built and deployed to GitHub Pages and served via custom domain at [arfanrafeek.com](https://arfanrafeek.com).

---

## Project Structure

```text
finance-resume/
├── .github/
│   └── workflows/
│       └── deploy.yml      # Automated CI/CD pipeline for GitHub Pages
├── content/
│   └── _index.md           # Resume content, skills, work history, and education
├── static/
│   └── CNAME               # Custom apex domain pointer (arfanrafeek.com)
├── themes/
│   └── PaperMod/           # PaperMod Hugo theme submodule
├── .gitignore              # Ignored Hugo build directories and locks
├── config.yml              # Site layout, theme settings, and metadata
└── README.md               # Repository documentation