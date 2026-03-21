# Stage 2 Report — Personal Website Setup

**Student:** Yusuf Abdulnasir Abubakar  
**Project:** Personal Website on GitHub Pages  
**Date:** 21 March 2026

---

## 1. Purpose

To add personal content to the Hugo-based website, including:
- Profile photo
- Biography
- Interests
- Education
- First blog post

---

## 2. Completed Tasks

### 2.1 Site Configuration

Updated `config.toml`:

```toml
baseurl = "https://abdulnasirpanda.github.io/"
languageCode = "en-us"
theme = "terminal"
title = "Yusuf Abdulnasir Abubakar"

[params]
  contentTypeName = "posts"
  fullWidthTheme = false
  centerTheme = false

[languages.en]
  subtitle = "Student at RUDN University"

2.2 Страница «О себе»

Создан файл content/about.md с:

Фотографией из GitHub аватара
Биографией
Интересами
Образованием
markdown
---
title: "About"
---

![My photo](https://github.com/abdulnasirpanda.png){: width="150"}

## About Me

Hello! I'm Yusuf Abdulnasir Abubakar, a student at RUDN University studying Computer Science.

## Interests
- Linux system administration
- Git and version control
- Web development

## Education
**RUDN University** (2025 — present)
- Faculty of Physics, Mathematics and Natural Sciences
- Computer Science
Рисунок 1 — Страница «О себе» с фотографией

2.3 Первый пост в блоге

Создан файл content/posts/first-post.md:

markdown
---
title: "My First Post"
date: 2026-03-21
---

## Welcome to My Site

Hello! I'm Yusuf Abdulnasir Abubakar, a student at RUDN University.

## What I'm Learning
- Linux system administration
- Git and version control
- Hugo static site generator
- GitHub Pages
Рисунок 2 — Первый пост в блоге

3. Скриншоты

Шаг	Скриншот
Главная страница	https://screenshots/stage2-home.png
Страница «О себе»	https://screenshots/stage2-about.png
Блог	https://screenshots/stage2-blog.png
4. Сайт в интернете

Сайт доступен по адресу:
https://abdulnasirpanda.github.io

5. Выводы

Этап 2 выполнен. На сайте теперь есть:

Личная информация с фотографией
Биография и интересы
Информация об образовании
Первый пост в блоге
Весь контент размещён на GitHub Pages и доступен онлайн. 
