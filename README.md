# xiaokefly.github.io

Personal portfolio of **Xunqian Liu** — Senior Backend Engineer (Java · Go · Python) building high-concurrency distributed systems and enterprise AI/LLM applications. Based in Beijing, China (GMT+8).

**Live:** [xiaokefly.github.io](https://xiaokefly.github.io) · also served at [www.xiaokefly.cn](https://www.xiaokefly.cn)

## Stack

Zero-dependency, zero-build static site — just HTML, CSS and a sprinkle of vanilla JS:

- Single-file portfolio (`index.html`) with inline CSS/JS — no frameworks, no external fonts or CDNs, loads fast anywhere in the world
- Dark "terminal" theme, system font stack + monospace accents
- Reveal-on-scroll via `IntersectionObserver`, typewriter hero, respects `prefers-reduced-motion`
- Accessible: semantic HTML, keyboard focus states, `aria` labels
- Custom styled 404 (`404.html`)

## Sections

1. **About** — quick intro, availability, and a terminal-style avatar card
2. **Toolbox** — skills grouped by category
3. **Experience** — Lenovo · DCE Feichuang (Dalian Commodity Exchange group) · JD Cloud · Hillstone Networks
4. **Projects** — selected, sanitized-for-public work: business process middle-platform, RAG Q&A system, unified portal & integration, cloud WAF rule engine
5. **Contact** — email + GitHub

## Deploy

```bash
# Aliyun server (www.xiaokefly.cn): files at /var/www/xiaokefly, nginx + TLS cert
# GitHub Pages: push to main → live in ~1 min
```

## License

Code: MIT. Content © Xunqian Liu.
