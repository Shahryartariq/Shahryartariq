# Hi, I'm Muhammad Shehryar (Sherry)

Full-stack developer at VisionTech in Islamabad, Pakistan. I build web apps with **TypeScript, React, Next.js, Node.js and Django**, and ship each one with tests, CI and a live URL. Right now I'm going deeper into **blockchain and AI**.

**[Portfolio: shehryartariq.vercel.app](https://shehryartariq.vercel.app)** · [LinkedIn](https://www.linkedin.com/in/muhammadshehryartariq/)

---

## Featured: Bitebox

**[Bitebox](https://github.com/Shahryartariq/bitebox) · [live demo](https://bitebox-one.vercel.app)**

A recipe website with an AI kitchen helper. Search about 800 recipes from around the world, including Pakistani favourites written for home kitchens, or paste a link from any recipe site.

<a href="https://bitebox-one.vercel.app"><img src="https://raw.githubusercontent.com/Shahryartariq/bitebox/main/docs/screenshots/home.jpg" alt="Bitebox home page with recipe search and Pakistani favourites" width="80%"></a>

- **Cook with what you have.** Add the ingredients in your kitchen and Bitebox ranks recipes by how many of them each one uses and how little else you'd need to buy.
- **Swap a missing ingredient.** One tap suggests replacements with amounts for that recipe, and says how the taste or texture changes.
- **Ask the kitchen helper.** "Make it spicier", "cook it without oil", "make it vegetarian", or your own question. Answers stream in as they're written.
- **Import any recipe link.** Bitebox reads the schema.org Recipe data most food sites publish and shows it in the same view, with a link back to the publisher. The server-side fetch is guarded against request forgery.
- **Made for the kitchen.** Scale amounts with proper kitchen fractions, save recipes without an account, print a clean copy, light and dark themes.

**Stack:** Next.js 16, React 19, TypeScript, Tailwind CSS 4, Vercel AI SDK with Google Gemini, Neon Postgres, Vitest, Playwright with axe.

## Projects

### AI

| Project | What it does | Stack |
|---|---|---|
| **[Satscope](https://github.com/Shahryartariq/satscope)** · [live](https://satscope.vercel.app) | Bitcoin wallet checkup. Finds inscriptions and Runes at risk of being spent by accident and fixes them in one signed transaction (PSBT); proves address ownership with BIP-322. | Next.js 16, TypeScript, bitcoinjs, LaserEyes, Vitest, Playwright |
| **[Authforge](https://github.com/Shahryartariq/authforge)** · [live](https://getauthforge.vercel.app) | Auth to drop into any new Next.js app: email and password, Google and GitHub, two-factor, passkeys, roles and an admin panel. | Next.js 16, Better Auth, PostgreSQL, Drizzle or Prisma, Playwright |
| **[Playpace](https://github.com/Shahryartariq/playpace)** · [live](https://getplaypace.vercel.app) | How long a YouTube playlist takes at any speed, and the slowest speed that fits your time. 12 languages, including Urdu and Arabic. | Next.js 16, TypeScript, YouTube Data API, Vitest, Playwright |
| **[Plainplay](https://github.com/Shahryartariq/plainplay)** · [live](https://plainplay.vercel.app) | YouTube without the rabbit hole: search and watch with no feed, no recommendations and no comments. Opens any video or playlist link, covers YouTube's pause and end-screen suggestions, and remembers where you stopped. Light, dark and night themes. | Next.js 16, TypeScript, YouTube Data and IFrame Player APIs, Vitest, Playwright |
| **[Zaproom](https://github.com/Shahryartariq/zaproom)** · [live](https://zaproom.vercel.app) | Video, voice and text chat in the browser with no sign-up: a live lobby of rooms, a global chat with private messages, text-only rooms and random 1-to-1 stranger chat. Screen share, reactions, typing indicators, seen ticks and a choice of notification sounds. | Next.js 16, TypeScript, LiveKit (WebRTC and data channels), Vitest, Playwright |
| **[Hashwire](https://github.com/Shahryartariq/hashwire)** · [live](https://hashwire.vercel.app) | Crypto news by blockchain. 22 networks, each with its own page, live price and 24h change. Reads 38 sources every 15 minutes and groups reports of the same story. | Next.js 16, TypeScript, CoinGecko API, Vitest, Playwright |
| **[Tensorwire](https://github.com/Shahryartariq/tensorwire)** · [live](https://tensorwire.vercel.app) | Today's AI news in one feed. 59 sources from AI labs, newsrooms and builders, with official lab posts marked and duplicate coverage grouped. | Next.js 16, TypeScript, RSS/Atom parsing, Vitest, Playwright |
| **[Skycast](https://github.com/Shahryartariq/skycast)** · [live](https://getskycast.vercel.app) | Weather for any city: now, next 24 hours, 5-day forecast and air quality, with a page for each major city. | Next.js 16, TypeScript, OpenWeather API, Vitest, Playwright |
| **[Tensorwire](https://github.com/Shahryartariq/tensorwire)** · [live](https://tensorwire.vercel.app) | Today's AI news on one page. Reads 58 feeds from AI labs, newsrooms and independent builders every 15 minutes, and lists each story once with every source. | Next.js 16, TypeScript, RSS/Atom parsing, Vitest, Playwright |
| **[TidyText](https://github.com/Shahryartariq/tidytext)** · [live](https://tidytext.vercel.app) | Free, private text cleaner. Fixes PDF line breaks, removes extra spaces and duplicates, fixes grammar, paraphrases and counts words, all in the browser. | Django, vanilla JS, Transformers.js, Docker |

### Blockchain

| Project | What it does | Stack |
|---|---|---|
| **[Satscope](https://github.com/Shahryartariq/satscope)** · [live](https://satscope.vercel.app) | Bitcoin wallet checkup. Finds inscriptions and Runes at risk of being spent by accident and fixes them in one signed transaction (PSBT); proves address ownership with BIP-322. | Next.js 16, TypeScript, bitcoinjs-lib, LaserEyes, Vitest, Playwright |
| **[Hashwire](https://github.com/Shahryartariq/hashwire)** · [live](https://hashwire.vercel.app) | Crypto news by blockchain. 22 networks, each with its own page, live price and 24h change. Reads 38 feeds every 15 minutes and groups reports of the same story. | Next.js 16, TypeScript, CoinGecko API, Vitest, Playwright |
| **[Portfolio](https://github.com/Shahryartariq/portfolio)** · [live](https://shehryartariq.vercel.app) | My portfolio. The experience timeline is a hash-linked chain you can verify in the browser, the contact form does proof of work before sending, and my GitHub contributions render as a 3D city. | Next.js 16, TypeScript, three.js, Web Crypto, Web Workers |

### Real-time and social

| Project | What it does | Stack |
|---|---|---|
| **[Zaproom](https://github.com/Shahryartariq/zaproom)** · [live](https://zaproom.vercel.app) | Video, voice and text chat in the browser with no sign-up: a live lobby of rooms, a global chat with private messages, text-only rooms and random 1-to-1 stranger chat. | Next.js 16, TypeScript, LiveKit (WebRTC), Postgres, Vitest, Playwright |
| **[Flexit](https://github.com/Shahryartariq/flexit)** · [live](https://getflexit.vercel.app) | A feed for sharing what you made, learned or achieved, in any skill. Live feed, likes, comments and notifications. Every rule, from row level security to rate limits, is enforced in the database. | Next.js 16, Supabase (Postgres, Auth, Storage, Realtime), Zod, Vitest, Playwright |
| **[Whisperbox](https://github.com/Shahryartariq/whisperbox)** · [live](https://getwhisperbox.vercel.app) | Ask a question, share the link and read anonymous answers as they arrive. Nobody signs up. Firestore security rules do the protecting, and they have their own tests. | Next.js 16, Firebase (Firestore, Anonymous Auth), Vitest, Playwright |

### Everyday tools

| Project | What it does | Stack |
|---|---|---|
| **[Listzero](https://github.com/Shahryartariq/listzero)** · [live](https://listzero.vercel.app) | A to-do list for busy minds. Quick add reads the date, priority and list from a sentence, Today shows one number to bring to zero, and focus mode puts one task on screen. Works offline, syncs across devices, supports shared lists. | React 19, TypeScript, Vite, Better Auth, Drizzle, Postgres, Vitest, Playwright |
| **[Playpace](https://github.com/Shahryartariq/playpace)** · [live](https://getplaypace.vercel.app) | How long a YouTube playlist takes at any speed, with daily watch plans you can add to your calendar. 12 languages, including Urdu and Arabic. | Next.js 16, TypeScript, YouTube Data API, Vitest, Playwright |
| **[Plainplay](https://github.com/Shahryartariq/plainplay)** · [live](https://plainplay.vercel.app) | YouTube without the rabbit hole. Search, watch and leave: no feed, no recommendations, no comments, no Shorts. Saves your place and turns playlists into courses. | Next.js 16, TypeScript, YouTube Data API, Vitest, Playwright |
| **[Skycast](https://github.com/Shahryartariq/skycast)** · [live](https://getskycast.vercel.app) | Pakistan weather for 50 cities: live conditions, 5-day forecasts, air quality and ten years of climate data. The page colour follows the real sky. | Next.js 16, TypeScript, OpenWeather, Open-Meteo, Postgres, Vitest, Playwright |
| **[Luckbox](https://github.com/Shahryartariq/luckbox)** · [live](https://luckbox-kappa.vercel.app) | Eight browser games, from Blackjack and Mines to Sudoku, 2048 and an unbeatable Tic Tac Toe. No sign-up; your records stay in your browser. | TypeScript (no framework), Vite, Vitest, Playwright |

### Developer tools

| Project | What it does | Stack |
|---|---|---|
| **[Authforge](https://github.com/Shahryartariq/authforge)** · [live](https://getauthforge.vercel.app) | Auth to drop into any new Next.js app: email and password, Google and GitHub, two-factor, passkeys, roles and an admin panel. | Next.js 16, Better Auth, PostgreSQL, Drizzle or Prisma, Playwright |
| **[Wipeout](https://github.com/Shahryartariq/wipeout-dev)** · [site](https://getwipeout.vercel.app) | Windows app that deletes folders Windows won't let you delete. Names the dev server, terminal or app holding a folder, stops it with one click, and wipes `node_modules` fast. | Electron, Node.js, C#, PowerShell |
| **[Seekvo](https://github.com/Shahryartariq/seekvo)** · [site](https://seekvo.vercel.app) | File search and cleanup for Windows that reads the NTFS index directly. In development: the search engine is written, and the site has a working demo. | Rust, Next.js 16, TypeScript |

**What the Next.js apps have in common:** strict TypeScript, unit and end-to-end tests on desktop and mobile (including automated accessibility checks), GitHub Actions CI, a strict Content Security Policy, and SEO basics (sitemap, Open Graph images, canonical URLs).

## Open source

Pull requests I've opened, waiting for review:

- **better-auth:** [stop uuid id defaults from causing Prisma and Drizzle schema drift](https://github.com/better-auth/better-auth/pull/12944)
- **better-auth:** [load auth configs that import `server-only`](https://github.com/better-auth/better-auth/pull/12945)
- **apostrophe:** [keep sanitize-html `transformTags` names from leaking into later closing tags](https://github.com/apostrophecms/apostrophe/pull/5782)

## Other work

- **[FL_Research_Demo](https://github.com/Shahryartariq/FL_Research_Demo)**: research demo that uses smart contracts to secure federated learning.
- **[PlantsHome](https://github.com/Shahryartariq/plantshome)**: Android plant-care app in Java with Firebase Auth: daily care tasks, badges and email-verified accounts.

## Tech I use

- **Languages:** TypeScript, JavaScript, Python, Rust, SQL, Java
- **Frontend:** React, Next.js (App Router, Server Components), Vite, Tailwind CSS, accessible HTML and CSS
- **Backend:** Node.js, Express, Django, REST APIs, OAuth 2.0, Better Auth, Auth.js
- **Data:** PostgreSQL (Neon, Supabase), MySQL, MongoDB, Firestore, Prisma, Drizzle
- **Real-time:** WebRTC (LiveKit), Supabase Realtime, Socket.IO
- **AI:** Vercel AI SDK, Google Gemini, Transformers.js
- **Blockchain:** Bitcoin PSBTs, BIP-322, Ordinals and Runes, smart contracts
- **Testing and quality:** Vitest, Playwright, axe-core, Lighthouse
- **DevOps:** Docker, GitHub Actions, Jenkins, Linux, Vercel, AWS EC2, Google Cloud

## Get in touch

Open to full-stack roles and freelance work. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/muhammadshehryartariq/).
