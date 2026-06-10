# GSAP Playground 

> An open-source animation component library built with **Next.js**, **GSAP**, and **Lenis** — for developers who want to learn and build modern web animations together.

**[Live Demo](#)** • **[Contributing Guide](#contributing)** • **[Roadmap](#roadmap)**

---

## What is this?

A community-driven collection of reusable, well-documented animation components. Clone it, learn from it, contribute to it. Whether you're just starting with animations or you're a seasoned dev — you're welcome here.

---

## ✨ Animation Components

| Component | Description |
|-----------|-------------|
| **Gravity Drop** | Physics-based falling animations with realistic bounce |
| **Scroll-Triggered Assemblies** | Content reveals synced with scroll position |
| **Border Reveal Effects** | Inward/outward border animations |
| **Horizontal Card Showcase** | Smooth carousel and card transitions |
| **Page Transitions** | Seamless route change animations |
| **Smooth Scrolling** | Lenis integration for native-feel scroll |

---

## 🛠 Tech Stack

- **[Next.js 16](https://nextjs.org/)** – React framework with SSR
- **[GSAP 3.15](https://gsap.com/)** – Professional animation library
- **[React 19](https://react.dev/)** – Modern UI
- **[Lenis 1.3](https://github.com/darkroom-digital/lenis)** – Smooth scroll
- **[Tailwind CSS 4](https://tailwindcss.com/)** – Styling
- **[TypeScript](https://www.typescriptlang.org/)** – Type safety

---

## 🚀 Quick Start

**Install pnpm if you don't have it:**
```bash
npm install -g pnpm
```

**Clone and run:**
```bash
git clone https://github.com/YOUR_ORG/gsap-playground.git
cd gsap-playground
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000)

---

## 🤝 Contributing

We welcome contributions of all kinds — new components, bug fixes, docs, performance improvements, accessibility enhancements.

### Steps

```bash
# 1. Fork the repo, then clone your fork
git clone https://github.com/YOUR_USERNAME/gsap-playground.git

# 2. Create a branch
git checkout -b feat/your-animation-name

# 3. Install & run
pnpm install && pnpm dev

# 4. Make changes, then commit
git commit -m "feat: add [animation name]"

# 5. Push and open a PR
git push origin feat/your-animation-name
```

### Adding a New Component

- Follow the folder pattern: `src/app/XX-component-name/`
- Include a `page.tsx` with your animation
- Add comments explaining the animation logic
- Check `gsapskills.md` for best practices

### Good First Contributions

- ✅ Add comments to existing animations
- ✅ Test on mobile/tablet and report issues
- ✅ Create animation variants with different easing
- ✅ Improve accessibility (`prefers-reduced-motion`, ARIA)
- ✅ Write docs or improve existing ones

### Code Guidelines

- Use CSS transforms (`x`, `y`, `scale`) — not layout properties
- Always respect `prefers-reduced-motion`
- Use TypeScript — no `any` types
- Write descriptive commit messages

---

## 🗺 Roadmap

- [ ] Export as npm component package
- [ ] Storybook integration
- [ ] Unit tests
- [ ] FLIP, Draggable, Morph animation patterns
- [ ] Community showcase gallery
- [ ] Animation starter templates

---

## 📚 Resources

- [GSAP Docs](https://gsap.com/docs/)
- [Next.js Docs](https://nextjs.org/docs)
- [Lenis Docs](https://lenis.studiofreight.com/)

---

## 📜 License

[MIT](LICENSE) — free to use in your own projects.

---

## 🌟 Contributors

Thanks to everyone who's contributed! ❤️

---

**Built in public. Animated with love. Open to all. 🚀**
