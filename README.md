<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:83eaf1,100:63a4ff&height=220&section=header&text=Pease%20Ernest&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Ernest%20Tech%20House%20%7C%20Browser%20Engines%20%7C%20Reverse%20Engineering&descAlignY=58&descSize=17" alt="Pease Ernest - Ernest Tech House"/>
</div>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3500&pause=1000&color=63A4FF&center=true&vCenter=true&width=640&lines=Building+a+browser+engine+from+scratch;C%2B%2B+%C2%B7+Zig+%C2%B7+Kotlin+%C2%B7+TypeScript;I+read+protocols+for+fun+%F0%9F%A4%93;I+make+the+impossible+things+%F0%9F%94%A5;Built+in+Kenya+%F0%9F%87%B0%F0%9F%87%AA" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://wa.me/254793859108"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
  <a href="https://t.me/ernesttechhouse"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="https://discord.gg/TUxBVQ7y"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
  <a href="https://www.npmjs.com/package/nothing-browser"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/></a>
  <a href="mailto:ernesttechhouse@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ernest12287&label=Profile+views&color=63a4ff&style=flat-square" alt="Profile views"/>
</p>

---

## 👋 Hey, I'm Ernest

I build things that most people look at and say *"you can't do that."* Then I do it, and then I write the documentation nobody asked for.

A year ago I was making websites. Today I'm writing a **browser engine in C++**. Somewhere in between, I got curious about how things *actually* work underneath, and I never recovered.

| | |
|---|---|
| 🔭 **Currently building** | **LucyN**, my own browser engine for [Nothing Browser](https://github.com/BunElysiaReact/nothing-browser). Headless pipeline done, window + painter next |
| 🌱 **Currently learning** | Zig, harder C++, and how far down the rabbit hole goes |
| 🧠 **Philosophy** | Don't use the abstraction. Read the protocol. Go to the source. |
| 🦸 **Hero** | [SaltyAom](https://github.com/SaltyAom), creator of Elysia.js. Obsessed admirer, no shame. |
| 😤 **Toxic relationship** | I hate Bun. I use Bun. We're working on it. |
| 🌍 **Based in** | Kenya 🇰🇪 |

---

## 🕳️ How I fell down the rabbit hole

```mermaid
flowchart LR
    A["🌐 Made websites"] --> B["🤔 How does JSX become HTML?"]
    B --> C["⚛️ Tried building a React-like thing: too hard, shelved"]
    C --> D["💬 whatsapp-web.js and a pile of WhatsApp bots"]
    D --> E["🕹️ Discovered you can control a browser and scrape"]
    D --> K["📡 Learned Baileys, then wanted the direct way it talks"]
    K --> L["🎯 Rule of life: go to the source"]
    E --> F["🧱 Cloudflare: blocked, blocked, blocked"]
    F --> G["🐷 Built Nothing Browser on Qt6"]
    G --> H["😤 Injecting JS into Qt was painful"]
    H --> I["🔧 Built my own engine: LucyN"]
    L --> I
```

---

## 🚀 What I've built

### 🌐 Nothing Browser
> *Does nothing... except everything that matters.*

![Qt6](https://img.shields.io/badge/Qt6-41CD52?style=flat-square&logo=qt&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Chromium](https://img.shields.io/badge/Chromium_WebEngine-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Version](https://img.shields.io/badge/latest-v0.1.9-63a4ff?style=flat-square)
![Platforms](https://img.shields.io/badge/Linux_%7C_macOS_%7C_Windows-333?style=flat-square)

A **scraper-first browser** for API reverse engineering, web scraping and automation research. Most browsers hide the web from you; this one exposes it.

- 🔍 Full network inspector: every request, response, WebSocket frame, cookie and storage write
- 📤 One-click export to Python `requests`, `curl_cffi`, cURL, JS fetch or raw HTTP
- 🎭 Engine-level fingerprint spoofing (UA, WebGL vendor, screen, hardware)
- 🔌 Community plugin system, in-app auto-updates, zero telemetry

| Phase | Engine | Status |
|---|---|---|
| **Phase 1** | Qt6 + Chromium WebEngine | ✅ Shipped (v0.1.9) |
| **Phase 2** | **LucyN**: my own engine, API and client | 🔨 In development, replaces the old automation library |

[📦 Repo](https://github.com/BunElysiaReact/nothing-browser) · [📚 Docs](https://nothing-browser-docs.pages.dev/guide/nothing-browser/) · [📥 Releases](https://github.com/BunElysiaReact/nothing-browser/releases)

---

### 👻 LucyN: the new phase of Nothing Browser
> *We don't care about beauty. We care about stealth, capture and truth.*

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![QuickJS](https://img.shields.io/badge/QuickJS-F7DF1E?style=flat-square&logoColor=black)
![SDL2](https://img.shields.io/badge/SDL2-22314E?style=flat-square)
![libcurl](https://img.shields.io/badge/curl--impersonate-073551?style=flat-square&logo=curl&logoColor=white)
![Status](https://img.shields.io/badge/status-pre--alpha_%7C_in_development-orange?style=flat-square)

The next phase of Nothing Browser: **my own engine, its own API and client, and everything around it**, built from the ground up because injecting JS into Qt kept fighting me. It replaces Chromium *and* the old automation library. One goal: **be invisible.**

**No Qt. No Chromium. No CDP. No remote debugging ports. No automation flags. No difference between headless and headful.** The engine always presents itself as a real, human-operated browser, because as far as it's concerned, it always is. No multi-gigabyte toolchains either: Gumbo, QuickJS, stb and Mongoose live in the repo as plain vendored source.

```
libcurl ──▶ Moonbug ──▶ NULLBYTE ──▶ TinyElysia ──▶ Dashboard
 (fetch)    (capture)     (sign)       (serve)
    │
    ▼
 HTML ──▶ Gumbo ──▶ DOM ◀──▶ QuickJS (DOM bridge)
```

**✅ Built and tested**

- 🕸️ **Moonbug**: LucyN *is* the HTTP client, so it captures decrypted traffic natively. No MITM certs, no proxy, nothing a page can reach
- 🔐 **NULLBYTE**: HMAC-SHA256 signing, so captured traffic can be proven untampered
- 🧩 **TinyElysia**: HTTP + WebSocket server in C/C++ (Elysia-inspired, zero Bun), serving a live capture dashboard on localhost
- 🌳 **DOM + QuickJS bridge**: `document`, `fetch`, XHR, cookies, timers and per-origin storage, enough to scrape JS-rendered pages with no pixels
- 💉 **LucyScript**: userscripts injected through a shell page, with `@run-at start|end`, plus before/after DOM snapshots and diffs
- 🎭 **Identity profiles**: one consistent "person" per session (UA, GPU, fonts, TLS/HTTP2 fingerprint via curl-impersonate, Chrome header order). Consistency beats randomness
- ⬇️ **Streaming downloads** straight to disk, using the same identity and cookie jar
- 🔌 **JS client** over newline-delimited JSON on stdio: no TCP port, nothing the page can see, and crash-safe promises
- 📦 **Portable by design**: all data lives in `nothing-data/` next to the binary. Delete the folder and the browser forgets everything

**🔨 Coming next**

- 👻 **Ghostful Mode**: no fake headless, just a real SDL window with the curtains drawn
- 🖼️ SoftwarePainter, block/inline layout and basic flexbox
- 🛡️ Built-in ad blocker at the request layer, cookie persistence
- 🧬 Fingerprint hardening and process isolation

```js
import Lucyn from "nothing-browser";

const a = new Lucyn({ profile: "default", ghostful: true, moonbug: true });

await a.visit("https://example.com");
const title = await a.extract("title");

a.moonbug.onRequest(req => console.log(req.url));   // the wiretap, from JS
await a.close();
```

**The rendering promise:** did it render? ✅ Is it pretty? 💩 Can I scrape it? 👻

*Stealth is a measured result, not a claim: every build is checked against tls.peet.ws, bot.sannysoft.com, CreepJS and BrowserLeaks, and a failing check becomes a ticket. Named after LucyN. She knows why.* 👀

---

### 🎬 NothingMovieStore
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![TMDB](https://img.shields.io/badge/TMDB-01B4E4?style=flat-square&logo=themoviedatabase&logoColor=white)
![Status](https://img.shields.io/badge/v1.1.0--beta-out_now-63a4ff?style=flat-square)

*Your midnight cinema, always open.* A free Android app for movies, series and anime: adless streaming, offline downloads, a native video player, TMDB metadata, live channels, and weekly Saturday patches. Rebuilt from scratch in **100% native Kotlin** because the old version kept crashing and I refused to ship something that falls over.

[🌐 Website](https://nothing-movies-website.pages.dev/) · [💬 Telegram](https://t.me/nothingmoviestore)

---

## 🛠️ Tech I use

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,zig,kotlin,ts,js&perline=6" alt="Systems and languages"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=qt,cmake,androidstudio,linux,git,vscode&perline=6" alt="Tooling"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=nodejs,bun,express,mongodb,mysql,postman&perline=6" alt="Backend"/>
</p>

---

## 📊 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ernest12287&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&title_color=63a4ff&icon_color=83eaf1" alt="GitHub stats"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ernest12287/Ernest12287/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ernest12287/Ernest12287/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/Ernest12287/Ernest12287/output/github-snake.svg" />
  </picture>
</p>

---

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=63A4FF&center=true&vCenter=true&width=480&lines=Thanks+for+visiting!+%F0%9F%91%8B;Let's+build+something+impossible+%F0%9F%9A%80" alt="Thanks for visiting" />
  </a>
  <br/>
  <sub>Part of the Nothing Ecosystem · Built in Kenya 🇰🇪</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:83eaf1,100:63a4ff&height=120&section=footer" width="100%" alt=""/>
