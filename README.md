# Ishraq Ahmed · Portfolio

**Built for growth. Grounded in data.**

My personal portfolio site. I'm a Computer Science student at Korea University with two years of fintech operations experience and a few hands-on data and ML projects.

🔗 **Live site:** [ahmedadit.github.io](https://ahmedadit.github.io)

---

## About me

- 🎓 B.S. Computer Science, **Korea University** (2024 – Feb 2027, expected). Transferred from North South University, Bangladesh (2021 – 2023).
- 💼 **Retention Staff at GmoneyTrans** (May 2024 – Mar 2026), a cross-border remittance app. Monthly transactions grew from 30k+ to 60k+ during my time there.
- 🌏 Grew up in the US, moved to Bangladesh, now based in Korea.
- 🗣️ English (IELTS 8.5), Bengali

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| **Rainfall Prediction Pipeline** | Collects 11 years of hourly weather data across 7 locations and turns it into a ~28k-row dataset. The rain target is redefined at the 90th percentile to fix class imbalance. | Python, Open-Meteo API, feature engineering |
| **[Excusinator](https://github.com/runeezubaida/excusinator)** | Text classifier that retrains itself from user corrections stored in a database. Co-built with Runee Zubaida. | TF-IDF, logistic regression, database |

## Site features

- Sticky sidebar that highlights the section you're currently reading
- English / 한국어 toggle that remembers your choice
- Staggered scroll animations and count-up stats
- Automatic dark mode
- Responsive layout for mobile and desktop
- Respects reduced-motion settings

## Tech

A single `index.html` with plain HTML, CSS and JavaScript. There are no frameworks and no build step.

Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [IBM Plex Sans KR](https://fonts.google.com/specimen/IBM+Plex+Sans+KR) and IBM Plex Mono.

## Run locally

```bash
git clone https://github.com/ahmedadit/ahmedadit.github.io.git
cd ahmedadit.github.io
open index.html   # or just double-click the file
```

## Editing content

- **English text** lives directly in the HTML.
- **Korean text** lives in the `KO` object inside the `<script>` tag. Each entry matches an element's `data-i18n` key.

To add a translated line, give the element a `data-i18n="your_key"` attribute and add `your_key: "한국어 텍스트"` to `KO`.

## Contact

📧 [adit.ahmed02@gmail.com](mailto:adit.ahmed02@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/ishraq-ahmed-456161282/) · 🐙 [GitHub](https://github.com/ahmedadit)
