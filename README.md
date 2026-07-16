# Daily Companion

A mindful productivity companion built with Tauri, React, and TypeScript.

## Description

Daily Companion is a desktop application designed to help you organize your daily life with intention — not just productivity for productivity's sake. It combines task management, habit tracking, journaling, and planning into a single, privacy-first application that runs natively on your machine.

## Core Philosophy

- **Mindful over Mechanical** — Productivity should serve your well-being, not the other way around.
- **Privacy-First** — Your data stays on your machine. No cloud dependency, no data mining.
- **Local by Default** — Built on Tauri and SQLite. Everything runs locally with no internet required.
- **Progressive Enhancement** — Start simple, grow into advanced features at your own pace.
- **Keyboard-First** — Designed for speed and efficiency without sacrificing clarity.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Desktop Shell | Tauri 2.x |
| Frontend | React 19 |
| Language | TypeScript |
| Bundler | Vite |
| Package Manager | pnpm |
| Styling | CSS |

## Project Structure

```
daily-companion/
├── src/                  # React application source
│   ├── App.tsx
│   ├── App.css
│   └── main.tsx
├── src-tauri/            # Tauri (Rust) backend
│   ├── src/
│   │   ├── lib.rs
│   │   └── main.rs
│   ├── Cargo.toml
│   └── tauri.conf.json
├── public/               # Static assets
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── .editorconfig
├── .gitattributes
├── .gitignore
└── LICENSE
```

## Development Workflow

```bash
# Install dependencies
pnpm install

# Start the development server with Tauri window
pnpm tauri dev

# Build for production
pnpm tauri build
```

## Roadmap

| Sprint | Theme | Focus |
|--------|-------|-------|
| Sprint 1 | Foundation | Repository standards, project setup, CI |
| Sprint 2 | Shell | App shell, sidebar, routing, theme system |
| Sprint 3 | Tasks | Task list CRUD, filtering, due dates |
| Sprint 4 | Habits | Habit tracking, streaks, check-in system |
| Sprint 5 | Journal | Daily journal, markdown editor, entries |
| Sprint 6 | Dashboard | Home dashboard, widgets, weekly review |
| Sprint 7 | Data | SQLite, persistence, import/export |
| Sprint 8 | Sync | Optional sync layer, backup, restore |
| Sprint 9 | Polish | Animations, accessibility, performance |
| Sprint 10 | Ship | Testing, packaging, store submission |

## Getting Started

> **Note:** This section will be expanded once the first stable prototype is available.

To run the project locally:

1. Ensure you have Rust, Node.js, and pnpm installed.
2. Clone the repository.
3. Run `pnpm install` to install dependencies.
4. Run `pnpm tauri dev` to launch the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.