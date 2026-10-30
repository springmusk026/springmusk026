<div align="center">

```
██████╗  █████╗ ███████╗ █████╗ ███╗   ██╗████████╗ █████╗
██╔══██╗██╔══██╗██╔════╝██╔══██╗████╗  ██║╚══██╔══╝██╔══██╗
██████╔╝███████║███████╗███████║██╔██╗ ██║   ██║   ███████║
██╔══██╗██╔══██║╚════██║██╔══██║██║╚██╗██║   ██║   ██╔══██║
██████╔╝██║  ██║███████║██║  ██║██║ ╚████║   ██║   ██║  ██║
╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝
```

**`Software Engineer — Android · Systems · Reverse Engineering`**

*Kathmandu, Nepal · NxP Studio*

[![](https://img.shields.io/badge/-@springmusk-1DA1F2?style=flat-square&logo=telegram&logoColor=white)](https://t.me/springmusk)
[![](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://np.linkedin.com/in/basanta-sapkota-57529923b)
[![](https://img.shields.io/badge/-Blog-FF5722?style=flat-square&logo=rss&logoColor=white)](https://basantasapkota026.com.np)
[![](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:springmusk@gmail.com)
[![](https://komarev.com/ghpvc/?username=springmusk026&style=flat-square&color=555)](https://github.com/springmusk026)

</div>

---

I build Android apps, backend services and, lately, small native Mac tools. Most of my open-source work is low-level tooling: Unity IL2CPP internals, native Android code, ADB automation.

Five years in, across mobile, systems and web. Currently learning Rust.

<br/>

## Projects

### Mac menu bar tools

Small, local-only utilities. Each is a menu bar app plus a CLI, with no network access and no accounts.

<table>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Portside">Portside</a></strong></td>
    <td>Every dev server running on your Mac, which project it belongs to, and a one-click stop.</td>
    <td><code>Swift</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Sweepside">Sweepside</a></strong></td>
    <td>Finds the gigabytes old projects hold in <code>node_modules</code>, <code>.venv</code>, <code>target</code> and DerivedData, and moves them to the Trash with undo.</td>
    <td><code>Swift</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Peekside">Peekside</a></strong></td>
    <td>A timeline of which apps used your microphone and camera today, and which can read what you type.</td>
    <td><code>Swift</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/ClaudeMeter">ClaudeMeter</a></strong></td>
    <td>Claude Code usage in the menu bar: plan limits, live sessions and cost.</td>
    <td><code>Swift</code></td>
  </tr>
</table>

### Reverse engineering

Tools for inspecting Unity IL2CPP binaries and protecting Android apps. These have the most stars.

<table>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Il2CppDumper-Python">Il2CppDumper-Python</a></strong></td>
    <td>Extracts type, method and field metadata from Unity IL2CPP games.</td>
    <td><code>Python</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Frida-Il2cpp-Dumper">Frida-Il2cpp-Dumper</a></strong></td>
    <td>Dumps IL2CPP metadata from a running process with Frida, for stripped binaries without symbols.</td>
    <td><code>TypeScript</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Android-Native-Il2cppDumper">Android-Native-Il2cppDumper</a></strong></td>
    <td>The same dump on the phone itself: a Compose app with a C++20 core. No PC, no root.</td>
    <td><code>Kotlin</code> <code>C++</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Dex2C-Tool">Dex2C</a></strong></td>
    <td>Converts Android DEX bytecode to native C/C++ so app logic is harder to reverse. Has an <a href="https://github.com/springmusk026/Dex2C-Android">Android client</a>, a <a href="https://github.com/springmusk026/dex2c-web">web front end</a> and a <a href="https://github.com/springmusk026/Dex2C-Backend">backend</a>.</td>
    <td><code>Kotlin</code> <code>JS</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/libmain.so">libmain.so</a></strong></td>
    <td>Source for <code>libmain.so</code>, the native loader in Unity's Android games.</td>
    <td><code>C++</code></td>
  </tr>
</table>

### Android and web

<table>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/AntiBloater">AntiBloater</a></strong></td>
    <td>Removes carrier and OEM bloatware without root. Opens a local ADB connection and runs the <code>pm uninstall</code> commands you pick.</td>
    <td><code>Kotlin</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/CloudEdge">CloudEdge</a></strong></td>
    <td>A blog and CMS that runs entirely on Cloudflare: Workers, D1, R2, KV and Durable Objects.</td>
    <td><code>TypeScript</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Open-Monitor-YT">Open-Monitor-YT</a></strong></td>
    <td>Self-hosted tool for keeping an eye on competing YouTube channels.</td>
    <td><code>TypeScript</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/Anthropic-Adapter">Anthropic-Adapter</a></strong></td>
    <td>A small Bun service that accepts Anthropic Messages API requests and forwards them to an OpenAI-compatible backend.</td>
    <td><code>TypeScript</code></td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/springmusk026/X-Pense">X-Pense</a></strong></td>
    <td>Expense tracker with categories, recurring payments and per-card spending. Expo and React Native.</td>
    <td><code>TypeScript</code></td>
  </tr>
</table>

<br/>

## Stack

<table>
  <tr>
    <td valign="top" width="25%">

**Systems**
```
C / C++
Rust (learning)
Linux internals
ADB / Frida
IL2CPP / Unity
```

  </td>
    <td valign="top" width="25%">

**Apps**
```
Kotlin / Java
Jetpack Compose
Swift / SwiftUI
Flutter
React Native
```

  </td>
    <td valign="top" width="25%">

**Web**
```
TypeScript
React / Next.js
Node.js / Bun
Laravel / PHP
Tailwind CSS
```

  </td>
    <td valign="top" width="25%">

**Infrastructure**
```
Cloudflare
AWS / GCP
Docker
MySQL / MongoDB
Linux (Debian)
```

  </td>
  </tr>
</table>

<br/>

## Writing

I write about systems, Android and developer tools at [basantasapkota026.com.np](https://basantasapkota026.com.np). Recent:

- [I left ChatGPT + the Gemini app for RikkaHub — full control on Android](https://www.basantasapkota026.com.np/2026/03/i-left-chatgpt-gemini-app-for-rikkahub.html)
- [Issue tracking is dead? The shift to context + agents](https://www.basantasapkota026.com.np/2026/03/issue-tracking-is-dead-is-kind-of.html)
- [Top 10 Agentic Coding Tools in 2026](https://www.basantasapkota026.com.np/2026/03/top-10-agentic-coding-tools-in-2026-dev.html)
- [Signals vs Hooks: What Changes for React Devs?](https://www.basantasapkota026.com.np/2026/03/signals-vs-hooks-what-changes-for-react.html)
- [Router Security: Your Wi-Fi Password Isn't the Whole Story](https://www.basantasapkota026.com.np/2026/03/router-security-your-wifi-password-isnt.html)

<br/>

## Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=springmusk026&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=springmusk026&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
</div>

<br/>

---

<div align="center">
<sub>
  <a href="mailto:springmusk@gmail.com">springmusk@gmail.com</a>
  &nbsp;·&nbsp;
  <a href="https://t.me/springmusk">Telegram</a>
  &nbsp;·&nbsp;
  <a href="https://np.linkedin.com/in/basanta-sapkota-57529923b">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://www.facebook.com/spring.musk/">Facebook</a>
</sub>
</div>
