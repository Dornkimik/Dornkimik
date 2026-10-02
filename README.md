# DevOminik

Software developer focused on privacy-respecting web applications, practical cryptography, and desktop automation. I also build games and game mods in C# and Unity.

## Featured project

### [SilenzaChat](https://github.com/Dornkimik/SilenzaChat) · [silenzachat.cc](https://silenzachat.cc)

An anonymous chat platform with public rooms and end-to-end encrypted private conversations. Visitors can join without an email address or real name.

- **Client-side encryption.** Private chats and temporary rooms are encrypted in the browser using TweetNaCl. The server relays ciphertext only and administrators cannot read private messages.
- **Metadata removal.** Image, video, and audio attachments are stripped of EXIF, GPS, XMP, ICC, and container metadata by rewriting the file at the byte level, without re-encoding the content.
- **Ephemeral storage.** Message history is kept in memory, attachments expire within 24 hours, and encrypted payloads are padded to coarse size classes.
- **Temporary rooms.** Open or invite-only group chats with per-member encryption, ownership transfer, and moderation controls.
- **Key verification.** Users can compare identity codes out of band to confirm encryption keys.
- **Hardened backend.** Hashed session bans, trusted-proxy handling, IPv6-aware rate limiting, and automated coverage with the Node.js test runner and Playwright.

Built with Node.js and vanilla JavaScript, with a single runtime dependency.

## Other projects

| Project | Description | Stack |
| --- | --- | --- |
| [gnome-calendar-integration](https://github.com/Dornkimik/gnome-calendar-integration) | Omarchy bar widget showing the next GNOME Calendar event, plus a Codex skill for creating and managing events through Evolution Data Server. | Python |
| [BitburnerScrips](https://github.com/Dornkimik/BitburnerScrips) | Automation scripts for the programming game Bitburner. | JavaScript |
| [Chess-Challenge](https://github.com/Dornkimik/Chess-Challenge) | Custom chess bot implementation. | C# |
| [Cube Simulation](https://saubstauga.itch.io/cube-simulation) | Small simulation project, playable on itch.io. | Unity |
| [Cubedown Shooter](https://saubstauga.itch.io/cubedown-shooter) | Top-down shooter, playable on itch.io. | Unity |
| [Password_Generator](https://github.com/Dornkimik/Password_Generator) | Password generator with an overlay interface. | C# |
| [PseudoEncrypter](https://github.com/Dornkimik/PseudoEncrypter) | Text obfuscation tool that generates a randomized lookup table for decoding. | C# |

## Technologies

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
