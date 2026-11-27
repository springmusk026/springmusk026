<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="742" alt="Basanta Sapkota, Kathmandu, Nepal. The name and city are shown as the decoded column of a hex dump.">
</picture>

I'm a software engineer at NxP Studio in Kathmandu. My work splits two ways: taking software apart (Unity IL2CPP, native Android, DEX bytecode) and building small tools that run on your own device, with no account and nothing phoning home.

Five years in, across mobile, systems and web. Currently learning Rust.

[Website](https://springmusk.dev) · [Blog](https://basantasapkota026.com.np) · [LinkedIn](https://np.linkedin.com/in/basanta-sapkota-57529923b) · [Telegram](https://t.me/springmusk) · [Email](mailto:springmusk@gmail.com)

## Now

- **[Locus](https://github.com/springmusk026/locus)** is a local-first AI agent for Android. You bring the model (an API key, a local server or on-device Gemma) and it gets a Linux workspace, a browser you can watch, sub-agents and an approval step before it acts.
- **[Composdown](https://github.com/springmusk026/Composdown)** is a Markdown renderer for Jetpack Compose built for streamed text. It parses incrementally, so a chat reply can arrive token by token without flicker.
- **[Tithimala](https://github.com/springmusk026/tithimala)** (तिथिमाला) is an open-source Nepali calendar for Android in Bikram Sambat, with no ads.

## Projects

### Reverse engineering

Tools for reading Unity IL2CPP binaries and for making Android apps harder to read. This is the work most people find me through.

| Project | What it does | Built with |
| :-- | :-- | :-- |
| **[Il2CppDumper-Python](https://github.com/springmusk026/Il2CppDumper-Python)** | Extracts type, method and field metadata from Unity IL2CPP games. | Python |
| **[Frida-Il2cpp-Dumper](https://github.com/springmusk026/Frida-Il2cpp-Dumper)** | Dumps the same metadata from a running process with Frida, for stripped binaries that have no symbols. | TypeScript |
| **[Android-Native-Il2cppDumper](https://github.com/springmusk026/Android-Native-Il2cppDumper)** | Does the dump on the phone itself: a Compose app over a C++20 core. No PC, no root. | Kotlin, C++ |
| **[Dex2C](https://github.com/springmusk026/Dex2C-Tool)** | Converts Android DEX bytecode to native C/C++ so app logic is harder to reverse. Comes with an [Android client](https://github.com/springmusk026/Dex2C-Android), a [web front end](https://github.com/springmusk026/dex2c-web) and a [backend](https://github.com/springmusk026/Dex2C-Backend). | Kotlin, JS |
| **[Imgui-Unity](https://github.com/springmusk026/Imgui-Unity)** | A Dear ImGui overlay for Unity games on Android. | C++ |
| **[libmain.so](https://github.com/springmusk026/libmain.so)** | Source for `libmain.so`, the native loader in Unity's Android games. | C++ |

### Mac menu bar tools

Each one is a menu bar app plus a CLI. They work locally, need no account and make no network requests.

| Project | What it does | Built with |
| :-- | :-- | :-- |
| **[Portside](https://github.com/springmusk026/Portside)** | Every dev server running on your Mac, which project it belongs to, and a one-click stop. | Swift |
| **[Sweepside](https://github.com/springmusk026/Sweepside)** | Finds the gigabytes old projects hold in `node_modules`, `.venv`, `target` and DerivedData, and moves them to the Trash with undo. | Swift |
| **[Peekside](https://github.com/springmusk026/Peekside)** | A timeline of which apps used your microphone and camera today, and which can read what you type. | Swift |
| **[ClaudeMeter](https://github.com/springmusk026/ClaudeMeter)** | Claude Code usage in the menu bar: plan limits, live sessions and cost. | Swift |

```sh
brew install springmusk026/tap/portside
```

### Android and web

| Project | What it does | Built with |
| :-- | :-- | :-- |
| **[AntiBloater](https://github.com/springmusk026/AntiBloater)** | Removes carrier and OEM bloatware without root. It opens a local ADB connection from the phone and runs the `pm uninstall` commands you pick. | Kotlin |
| **[CloudEdge](https://github.com/springmusk026/CloudEdge)** | A blog and CMS that runs entirely on Cloudflare: Workers, D1, R2, KV and Durable Objects. | TypeScript |
| **[Anthropic-Adapter](https://github.com/springmusk026/Anthropic-Adapter)** | A small Bun service that accepts Anthropic Messages API requests and forwards them to an OpenAI-compatible backend. | TypeScript |
| **[Open-Monitor-YT](https://github.com/springmusk026/Open-Monitor-YT)** | A self-hosted tool for keeping an eye on competing YouTube channels. | TypeScript |
| **[X-Pense](https://github.com/springmusk026/X-Pense)** | An expense tracker with categories, recurring payments and per-card spending. | React Native |

## Stack

- **Systems:** C and C++, Frida, ADB, IL2CPP internals, Linux
- **Apps:** Kotlin with Jetpack Compose, Swift with SwiftUI, Flutter, React Native
- **Web:** TypeScript, React and Next.js, Node and Bun, Laravel
- **Infrastructure:** Cloudflare Workers, AWS, GCP, Docker, MySQL, MongoDB

## Writing

I write about Android, AI tools and tech in Nepal at [basantasapkota026.com.np](https://basantasapkota026.com.np). The latest posts:

<!-- BLOG-POST-LIST:START -->
- [Google finally added new Claude models to Antigravity after the 4.6 series](https://www.basantasapkota026.com.np/2026/10/google-finally-added-new-claude-models.html)
- [Nepal's Government Tech Workers Are Failing Us: SSL Lapses, Data Leaks, and AI Slop Everywhere](https://www.basantasapkota026.com.np/2026/10/nepals-government-tech-workers-are.html)
- [Internet in Nepal Is Cheap — But at What Cost?](https://www.basantasapkota026.com.np/2026/09/internet-in-nepal-is-cheap-but-at-what.html)
- [Googlebook Is Here: Android Finally Comes to Your Laptop](https://www.basantasapkota026.com.np/2026/09/googlebook-is-here-android-finally.html)
- [Who Really Wants to Slow Down AI — And Why You Should Be Suspicious](https://www.basantasapkota026.com.np/2026/09/who-really-wants-to-slow-down-ai-and.html)
<!-- BLOG-POST-LIST:END -->

## Get in touch

Telegram is fastest: [@springmusk](https://t.me/springmusk). For anything longer, write to [springmusk@gmail.com](mailto:springmusk@gmail.com).
