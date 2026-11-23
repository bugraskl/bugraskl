# Buğra Şıkel

**Full-stack developer · Founder of Hano · Bursa, Türkiye**

I build production web applications, fintech dashboards and computer vision systems for manufacturing, from the database to the interface and from the camera to the production line.

Currently building **Hano**, an AI-powered family budgeting app (React Native · Supabase).

[![Website](https://img.shields.io/badge/bugra.work-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://bugra.work)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/bugraskl)
[![Email](https://img.shields.io/badge/bugraskl@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bugraskl@gmail.com)

[![Showreel '26: fifteen seconds on what I build](assets/showreel.webp)](https://bugra.work/#showreel)

<sub>Showreel '26, built in React with Remotion. [Watch it with sound on bugra.work →](https://bugra.work/#showreel)</sub>

---

### What I work on

- **Web platforms** — business applications with PHP/Laravel and TypeScript (Next.js, Fastify), REST APIs, MySQL and PostgreSQL
- **Fintech & data** — data pipelines and dashboards built on market and central bank data
- **Computer vision for manufacturing** — OpenCV-based inspection, anomaly detection, industrial camera and PLC integration
- **Automation & AI** — LLM-powered tools, tooling for AI coding agents, n8n workflows and desktop utilities

### Tools for AI coding agents

| Project | What it does | Stack |
|---|---|---|
| [**claude-code-office**](https://github.com/bugraskl/claude-code-office) | A live 3D office for your Claude Code sessions: every session is a room, every subagent a coworker at a desk, so you can see who is working, thinking, waiting for you or stuck. `npx claude-code-office` | Node.js · three.js · [npm](https://www.npmjs.com/package/claude-code-office) |
| [**telegram-agent**](https://github.com/bugraskl/telegram-agent) | Manage Codex and Claude Code from Telegram: resume a session on your Windows PC, read the recent conversation and send the next task from your phone | Node.js · Telegram Bot API |

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**eye-tracker**](https://github.com/bugraskl/eye-tracker) | Look at a monitor and your cursor and keyboard focus follow. Webcam-based switching for multi-monitor setups, fully offline on Windows, macOS and Linux | Python · OpenCV · Qt |
| [**habit-guard**](https://github.com/bugraskl/habit-guard) | Catches nail biting, mustache or hair pulling and face touching through your webcam and nudges you to stop. Private, offline and light on the CPU | Python · OpenCV · PySide6 |
| [**ubuntu-starter-script**](https://github.com/bugraskl/ubuntu-starter-script) | Turns a fresh Ubuntu 24.04 machine into a machine vision / HMI station in one command: Basler pylon, OpenCV, Siemens S7 (snap7), Apache, PHP and MySQL | Shell · Basler pylon · OpenCV |
| [**tcmb-reserve-terminal**](https://github.com/bugraskl/tcmb-reserve-terminal) | Tracks Turkish central bank reserves, swaps, liquidity and gold via EVDS and flags intervention signals, with an AI commentary layer | Next.js · Fastify · PostgreSQL |
| [**fon-scrapper**](https://github.com/bugraskl/fon-scrapper) | Pulls return data for 2,375+ Turkish investment and pension funds from Fintables, with interactive filters and Excel, PDF and CSV export | Python · Playwright |
| [**randevu-sistemi**](https://github.com/bugraskl/randevu-sistemi) | Appointment, client and payment management for psychologists and clinics, installable as a PWA with SMS notifications | PHP · MySQL |
| [**telegram-finance-tracker**](https://github.com/bugraskl/telegram-finance-tracker) | Log income and expenses in natural language via Telegram, track them on a web dashboard | Node.js · n8n · Docker |
| [**sweepkit**](https://github.com/bugraskl/sweepkit) | Honest disk cleanup for Windows and Linux: shows what is safe to delete and what it costs, deletes nothing until you confirm, no telemetry | Go · Wails |
| [**dusty**](https://github.com/bugraskl/dusty) | Frees up disk space without losing anything: finds files you haven't touched in a year, backs them up to Google Drive, OneDrive or any folder, verifies the copy, then deletes. Portable Windows exe | Python |
| [**win-quick-translator**](https://github.com/bugraskl/win-quick-translator) | Spotlight-style translator for Windows: press Ctrl+Space, type, and it translates between your language and English | Python |
| [**website-screenshot-recorder**](https://github.com/bugraskl/website-screenshot-recorder) | Captures full-page website screenshots, handling lazy loading, and turns them into smooth scrolling GIF or WebP animations | Python · Tkinter |
| [**file-categorizer**](https://github.com/bugraskl/file-categorizer) | Cross-platform desktop app that organizes files with deterministic rules, no AI | Electron · Python |
| [**wordpress-post-generator**](https://github.com/bugraskl/wordpress-post-generator) | Generates and publishes WordPress posts with Gemini, ChatGPT or Grok | Python · Flask |
| [**cv2-threshold-visualizer**](https://github.com/bugraskl/cv2-threshold-visualizer) | Interactive tool for tuning OpenCV thresholding parameters in real time | Python · OpenCV |

### n8n workflow projects

Production workflows from my self-hosted n8n, cleaned up and open-sourced as importable JSON with setup guides.

| Project | What it does | Stack |
|---|---|---|
| [**production-n8n-workflows**](https://github.com/bugraskl/production-n8n-workflows) | Small, auditable automations for self-hosters and small teams (security, monitoring, backups, GitHub, domains, alerts) with safe first runs, bounded retries and no exported credentials | n8n |
| [**n8n-grounded-blog-writer**](https://github.com/bugraskl/n8n-grounded-blog-writer) | Weekly WordPress posts on topics people actually search for: trend signals, Google-grounded research and a number check that blocks invented statistics | n8n · Gemini · WordPress REST |
| [**n8n-instagram-autopilot**](https://github.com/bugraskl/n8n-instagram-autopilot) | Turns a folder of food photos into designed Instagram posts, stories and a weekly AI reel; a decision model gates every caption before it goes live | n8n · Gemini · Veo · ffmpeg |
| [**n8n-instagram-reels-publisher**](https://github.com/bugraskl/n8n-instagram-reels-publisher) | Publishes Instagram Reels and video Stories from n8n with resumable upload, which works where fetching the video from a webhook URL fails | n8n · Instagram Graph API |
| [**n8n-gmail-ai-labeler**](https://github.com/bugraskl/n8n-gmail-ai-labeler) | Hourly Gmail labeling with a typed decision model: one decision per email, no broken JSON, fractions of a cent | n8n · Gmail API · OpenRouter |

### Smaller tools and snippets

[github-profile-pulse](https://github.com/bugraskl/github-profile-pulse) (dependency-free GitHub profile summary) ·
[computer-info](https://github.com/bugraskl/computer-info) (hardware details) ·
[smtp-tester](https://github.com/bugraskl/smtp-tester) ·
[php-eticaret-api](https://github.com/bugraskl/php-eticaret-api) ·
[laravel-blog-script](https://github.com/bugraskl/laravel-blog-script) ·
[database-logger-class](https://github.com/bugraskl/database-logger-class) ·
[php-number-to-text](https://github.com/bugraskl/php-number-to-text) ·
[php-license-key-generator](https://github.com/bugraskl/php-license-key-generator)

### Tech stack

**Languages** — Python · TypeScript · JavaScript · PHP · Go · SQL  
**Backend** — Laravel · Node.js · Fastify · REST APIs  
**Frontend & mobile** — Next.js · React · React Native (Expo)  
**Data** — MySQL · PostgreSQL · Supabase  
**Vision & AI** — OpenCV · PyTorch · TensorFlow · LLM APIs · Claude Code  
**Tooling** — Docker · Linux · Cloudflare · n8n
