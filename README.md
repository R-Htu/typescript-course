# 📘 TS Academy — TypeScript Course

A free, beginner-friendly TypeScript course built with pure HTML & CSS. No frameworks, no login, no paywall — just clear lessons you can open in any browser.

🔗 **Live Site:** [r-htu.github.io/typescript-course](https://r-htu.github.io/typescript-course/)

---

## 🗂️ Course Structure

The course is organized into **4 levels** across **17 lessons**.

### 🟢 Foundations — Lessons 1–6

| # | Lesson | Topics |
|---|--------|--------|
| 01 | What is TypeScript? | Intro, setup, compilation, first .ts file |
| 02 | Primitive Types | string, number, boolean, bigint, symbol, null, undefined |
| 03 | Arrays & Tuples | Type[], Array\<T\>, fixed-length tuples, array methods |
| 04 | Objects & Interfaces | Object typing, interfaces, optional & readonly properties |
| 05 | Functions | Parameter types, return types, optional & default params, rest |
| 06 | Union Types & Type Aliases | \| operator, type aliases, literal types |

### 🟡 Intermediate — Lessons 7–11

| # | Lesson | Topics |
|---|--------|--------|
| 07 | Classes | Access modifiers, inheritance, abstract classes, getters & setters |
| 08 | Generics | \<T\>, generic functions, interfaces, constraints |
| 09 | Enums | Numeric, string, and const enums |
| 10 | Type Narrowing | typeof, instanceof, in operator, type assertions |
| 11 | Modules | ES Modules, named/default exports, import types, project structure |

### 🟠 Advanced — Lessons 12–14

| # | Lesson | Topics |
|---|--------|--------|
| 12 | Utility Types | Partial, Required, Pick, Omit, Record, Exclude, ReturnType |
| 13 | Decorators | Class, method, property decorators, NestJS real-world usage |
| 14 | tsconfig.json | target, strict, paths, module, outDir, sourceMap, project configs |

### 🔴 Real World — Lessons 15–17

| # | Lesson | Topics |
|---|--------|--------|
| 15 | TypeScript + React | Props, useState, useRef, hooks, event types, custom hooks |
| 16 | TypeScript + Node.js | Express, typed requests, middleware, NestJS intro |
| 17 | Advanced Types | Conditional types, mapped types, template literals, infer |

---

## 📁 File Structure

```
typescript-course/
├── index.html                     ← Course homepage (all 17 lesson cards)
├── lessons-1-to-6.html            ← Lessons 1–6  (Foundations)
├── lessons-7-to-11.html           ← Lessons 7–11 (Intermediate)
├── utility-types.html             ← Lesson 12
├── decorators.html                ← Lesson 13
├── tsconfig.html                  ← Lesson 14
├── ts-react.html                  ← Lesson 15
├── ts-nodejs.html                 ← Lesson 16
├── advanced-types.html            ← Lesson 17
├── ts-course-widget.html          ← Embeddable course widget
├── ts-course-widget-tailwind.html ← Tailwind version of widget
└── README.md
```

---

## 🚀 Getting Started

### View Online

Visit the live site directly:
**https://r-htu.github.io/typescript-course/**

### Run Locally

No build steps needed — just clone and open:

```bash
git clone https://github.com/r-htu/typescript-course.git
cd typescript-course
# Open index.html in your browser
```

Or use **Live Server** in VS Code for the best experience.

---

## ✨ Features

- ✅ **17 lessons** from beginner to advanced
- ✅ **Syntax-highlighted code examples** throughout
- ✅ **Lesson navigation** — every page has ← Previous / Next → buttons
- ✅ **Mobile responsive** — works on any device
- ✅ **No dependencies** — pure HTML, CSS, and vanilla JS
- ✅ **Hosted free** on GitHub Pages
- ✅ **Open source** — fork and customize freely
- ✅ **Embeddable widget** for sharing on other sites

---

## 🛠️ Built With

- HTML5 & CSS3
- [Tailwind CSS](https://tailwindcss.com) (CDN) for the widget
- [Google Fonts](https://fonts.google.com) — JetBrains Mono, Syne, Fraunces, Space Grotesk, and more
- Hosted on [GitHub Pages](https://pages.github.com)

---

## 📖 How to Use This Course

1. Start at [Lesson 1](https://r-htu.github.io/typescript-course/lessons-1-to-6.html) — no prior TypeScript knowledge needed
2. Read each lesson and study the code examples
3. Try the code yourself in [TypeScript Playground](https://www.typescriptlang.org/play) or your local editor
4. Use the **Next Lesson →** button at the bottom of each page to continue
5. For hands-on practice, install TypeScript locally:

```bash
npm install -g typescript
tsc --version
```

---

## 🧩 Embeddable Widget

Want to share the course on your own website? Use the iframe embed:

```html
<iframe
  src="https://r-htu.github.io/typescript-course/ts-course-widget-tailwind.html"
  width="100%"
  height="420"
  frameborder="0"
  style="border-radius: 20px; max-width: 780px;"
></iframe>
```

---

## 🤝 Contributing

Found a typo or want to improve a lesson? Contributions are welcome!

1. Fork the repo
2. Make your changes
3. Open a Pull Request with a clear description

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [Ruth](https://github.com/R-Htu) · Free to learn, free to share

[🌐 Live Site](https://r-htu.github.io/typescript-course/) · [🐛 Report Issue](https://github.com/r-htu/typescript-course/issues)
