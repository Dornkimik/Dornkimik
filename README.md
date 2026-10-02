<h1 align="center">01001000 01101001 👋</h1>
<p align="center"><i>(that's "Hi" — I'm <b>Dominik</b>, aka <b>DevOminik</b>)</i></p>

<p align="center">
  I build things that keep secrets, automate my desktop, and occasionally make cubes suffer.
</p>

---

## 🤫 Currently building: [SilenzaChat](https://github.com/Dornkimik/SilenzaChat)

> **Talk freely. Leave no name.** → [silenzachat.cc](https://silenzachat.cc)

An anonymous chatroom with live public rooms and **end-to-end encrypted** private chats. No email, no real name, no account required — you show up as a random alias and start talking.

What I'm proud of under the hood:

- 🔐 **Browser-side encryption** — private chats and temporary rooms are encrypted in the browser with TweetNaCl. The server only ever relays ciphertext; even admins can't read them.
- 🧹 **Canvas-free metadata stripping** — photos, GIFs, video and audio get their EXIF/GPS, XMP, ICC profiles, container timestamps and encoder tags removed by rewriting the file container *at the byte level*. Pixels are never re-encoded.
- 🫥 **Ephemeral by design** — history lives in memory, attachments expire within 24h, and encrypted sizes are padded to coarse size classes.
- 🏠 **Temporary rooms** — open or invite-only, with per-member encryption, ownership transfer and kicks.
- 🪪 **Identity verification** — compare safety codes out-of-band to make sure you're talking to the right key.
- 🛡️ **Paranoid backend** — hashed session bans, trusted-proxy handling, IPv6-aware rate limiting, and a pile of Playwright browser checks on top of `node --test`.

Built with a deliberately tiny dependency footprint: plain **Node.js** + vanilla JS, one runtime dependency.

---

## 🧰 Other things I've made

| Project | What it is |
| --- | --- |
| 📅 [**gnome-calendar-integration**](https://github.com/Dornkimik/gnome-calendar-integration) | An Omarchy bar widget that shows your next GNOME Calendar event, plus a Codex skill to create/list/delete events via Evolution Data Server. Python + GObject. |
| 🧬 [**FewMoreTraits**](https://steamcommunity.com/sharedfiles/filedetails/?id=2894069326) | A RimWorld mod on the Steam Workshop that adds a few more traits to your colonists. ([source](https://github.com/Dornkimik/FewMoreTraits-Source)) |
| 💻 [**BitburnerScrips**](https://github.com/Dornkimik/BitburnerScrips) | My scripts for [Bitburner](https://store.steampowered.com/app/1812820/Bitburner/) — the game where you hack the world by writing actual JavaScript. |
| ♟️ [**Chess-Challenge**](https://github.com/Dornkimik/Chess-Challenge) | My entry for Sebastian Lague's tiny-chess-bot challenge. |
| 🟥 [**Cube Simulation**](https://saubstauga.itch.io/cube-simulation) | A small simulation of a cube's life. It's more philosophical than it sounds. |
| 🔫 [**Cubedown Shooter**](https://saubstauga.itch.io/cubedown-shooter) | A small, self-declared "trashy" top-down shooter made in Unity. Play it on itch.io. |
| 🔑 [**Password_Generator**](https://github.com/Dornkimik/Password_Generator) | A password generator… but with an overlay. |
| 🧾 [**PseudoEncrypter**](https://github.com/Dornkimik/PseudoEncrypter) | Encrypts a sentence and spits out a random lookup table to decode it — where the crypto rabbit hole started. |

---

## 🛠️ Stuff I work with

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white" />
</p>

---

<p align="center"><sub>01000010 01111001 01100101 👋</sub></p>
