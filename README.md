# Easy React with Vite: 18 React mini-apps

A collection of 18 small, self-contained React + Vite apps. Each folder is an independent project with its own README and a live demo on Vercel.

**Honest context:** these started as learning projects, built to practice one frontend concept at a time (state, effects, refs, API calls, CSS animation). They are small by design, not production products, but they show how I work with React fundamentals.

## Projects

| # | App | What it shows | Key React concepts | Live demo |
|---|-----|---------------|--------------------|-----------|
| 1 | [Rotating Navigation](rotating-navigation) | Page content rotates open to reveal a nav menu | useState, conditional CSS classes | [Demo](https://rotating-navigation-zeta.vercel.app/) |
| 2 | [Blurry Loading](blurry-loading) | Image un-blurs as a percentage counter advances | useEffect + interval cleanup, derived style values | [Demo](https://blurry-loading-delta.vercel.app/) |
| 3 | [Interactive Panels](interactive-panels) | Expanding image panels fed by a mock REST API | useEffect, Axios, json-server, fetch-on-mount | [Demo](https://interactive-panels.vercel.app/) |
| 4 | [Progress Steps](progress-steps) | Multi-step progress bar with Prev/Next | useState, derived UI state, disabled buttons | [Demo](https://progress-steps-psi.vercel.app/) |
| 5 | [Interactive Search Bar](interactive-search-bar) | Search input that expands on focus/click | useState, toggled classes, CSS transitions | [Demo](https://interactive-search-bar.vercel.app/) |
| 6 | [Scroll-Triggered Animation](scroll-triggered-animation) | Boxes slide in from the sides on scroll | useEffect, useRef, scroll listeners | [Demo](https://scroll-triggered-animation.vercel.app/) |
| 7 | [Interactive Split Section](interactive-split-section) | Two-panel hero that reacts to hover | useState, event handlers, component props | [Demo](https://interactive-split-section.vercel.app/) |
| 8 | [Animated Login Form](animated-login-form) | Floating labels animate on input focus | useState, controlled inputs, responsive CSS | [Demo](https://animated-login-form-ten.vercel.app/) |
| 9 | [Interactive Sound Board](interactive-sound-board) | Buttons play sounds, one at a time | useRef, HTMLAudioElement control | [Demo](https://interactive-sound-board.vercel.app/) |
| 10 | [Random Joke Generator](random-joke-generator) | Fetches a new dad joke on click | useEffect, Axios, async requests | [Demo](https://random-joke-generator-brown.vercel.app/) |
| 11 | [Event KeyCodes](event-keycodes) | Shows keyboard and mouse event data live | useEffect with event listeners and cleanup | [Demo](https://event-keycodes-brown.vercel.app/) |
| 12 | [FAQ App](faq-app) | Collapsible FAQ accordion | useState, list rendering, toggle state | [Demo](https://faq-app-rose.vercel.app/) |
| 13 | [Random Tag Selector](random-tag-selector) | Type comma-separated tags, app randomly picks one | useState, key events, timers, string parsing | [Demo](https://random-tag-selector.vercel.app/) |
| 14 | [Animated Navigation Menu](animated-navigation-menu) | Nav that expands/collapses with transitions | useState, CSS transitions | [Demo](https://animated-navigation-menu-six.vercel.app/) |
| 15 | [Social Media Counters](social-media-counters) | Animated follower counters | useEffect, intervals, state updates | [Demo](https://social-media-counters-beta.vercel.app/) |
| 16 | [Water Tracker](water-tracker) | Daily water intake with cup selection | useState, useEffect, localStorage persistence | [Demo](https://water-tracker-beryl-theta.vercel.app/) |
| 17 | [Movie App](movie-app) | Browse and search movies via TMDB API | Axios/fetch, env vars, search, reusable components | [Demo](https://movie-app-sigma-six-26.vercel.app/) |
| 18 | [Image Navigator](image-navigator) | Browse random images (Picsum API) back/forward | useEffect, API calls, state history | [Demo](https://image-navigator.vercel.app/) |

## Stack

React, Vite, JavaScript (ES6+), CSS, Axios, json-server (mock API in one app), ESLint. Deployed on Vercel.

## How to run

```bash
git clone https://github.com/GustavoVzla/Easy-React-with-Vite.git
cd Easy-React-with-Vite/<app-folder>
npm install
npm run dev
```

The Movie App needs a free TMDB API key: copy `movie-app/.env.example` to `movie-app/.env` and set `VITE_TMDB_API_KEY`. The Interactive Panels app uses `db.json` with json-server (see its README).

## Built by Gustavo Tejera

Web developer focused on React/Next.js, automation (n8n) and Web3. LinkedIn: https://www.linkedin.com/in/gustavotejera

License: MIT (see [LICENSE](LICENSE)).

## Resumen en español

Colección de 18 mini-apps en React + Vite, cada una en su carpeta con README y demo en vivo (Vercel). Nacieron como proyectos de aprendizaje para practicar conceptos concretos (estado, efectos, refs, llamadas a APIs, animaciones CSS). Para ejecutar: `npm install` y `npm run dev` dentro de cada carpeta; la app de películas requiere una clave gratuita de TMDB en `.env`.
