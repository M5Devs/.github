<div align="center">

# M5 DEV

**AI developer & creative studio.** Retro-gaming tooling, native systems software and anime models —
built in Cairo, shipped in the open, **never behind a paywall**.

[**Portfolio**](https://M5Devs.github.io) · [**Hugging Face**](https://huggingface.co/M5-Dev) · [**X**](https://x.com/M5Devs) · [**Dev.to**](https://dev.to/m5dev) · [**YouTube**](https://www.youtube.com/@m5devs) · [**Discord**](https://discord.gg/FYEjpcFYXc) · [**All repositories**](https://github.com/M5Devs?tab=repositories)

![Public repos](https://img.shields.io/badge/public_repos-40%2B-22d3ee?style=flat-square)
![Stars](https://img.shields.io/github/stars/M5Devs?style=flat-square&label=stars&color=22d3ee)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-9_models_8_datasets-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Forever free](https://img.shields.io/badge/forever_free-yes-8b5cf6?style=flat-square)

</div>

We ship the tool, publish the source, and charge nothing for it. No telemetry, no accounts,
no "pro" tier. If a project here needs a paid IDE, a cloud subscription or a signed vendor
blessing to build, we consider it broken.

---

> [!WARNING]
> **🛡️ Keep Android Open — the 2027 sideloading lockdown**
>
> Google is turning sideloading into a permission slip. From 2027, installing an app
> outside Play on a certified Android device will require its developer to be
> identity-verified by Google — with Google holding the list of who is allowed to build.
>
> That is the entire category we work in: emulators, ROM managers, portable runtimes,
> homebrew, twenty-year-old N-Gage prototypes. Every one of them lives or dies on
> "download the file and run it".
>
> Every Android build here stays buildable from source. Sign the letter.
>
> [![Keep Android Open](https://img.shields.io/badge/KEEP_ANDROID_OPEN-sign_the_letter-FF2D2D?style=for-the-badge&logo=android&logoColor=white)](https://keepandroidopen.org/)

---

## ⚡ Flagship projects

| Project | What it does | Stack | Version | Stars |
| :--- | :--- | :--- | :--- | ---: |
| [**OpenROM**](https://github.com/M5Devs/OpenROM) | Universal Retro Gaming Toolkit — convert, patch, compress and manage ROMs for PS1, PS2, Xbox, GameCube, Wii, Saturn and Sega CD. 20+ conversion paths, magic-byte platform detection, real CHD header parsing. Flutter GUI + headless CLI. | `Dart` · Flutter | `v4.1.0` | 326 |
| [**masa**](https://github.com/M5Devs/masa) | Build, lint, package (.dmg / .ipa) and run macOS Mach-O binaries on Linux, Windows and Android — without a Mac, Xcode or the $99/yr Apple tax. | `C11` | `v1.8.1` | 1 |
| [**vbx**](https://github.com/M5Devs/vbx) | Visual Basic 6, revived as a modern cross-platform language. Transpiles to native C99 at `-O2` with real dialogs, string functions and zero-dependency binaries. | `Go` → C99 | `v0.1.0-alpha` | 6 |
| [**VPortable**](https://github.com/M5Devs/VPortable) | Rootless, user-space Android virtualization and container engine: isolated guest ROMs, modular recovery flashing and sandboxing with zero host modification. | `Kotlin` · C | `main` | 4 |
| [**UMDPlay**](https://github.com/M5Devs/UMDPlay) | Cross-platform player and library for UMD Video ISOs: its own PSMF demuxer, H.264 + ATRAC3+ decode, no PSP firmware and no FFmpeg. | `C++` · Qt Quick | `v1.0.3` | 5 |
| [**GitInfo**](https://github.com/M5Devs/GitInfo) | Inspect any GitHub repo before you clone: formatted size (KB → GB), language breakdown, licences and health metrics. | `TypeScript` · Vite | `v3.0.0` | 1 |

**Licences:** GPL-3.0 for OpenROM, masa, vbx and VPortable · GPL-2.0 for UMDPlay · Apache-2.0 for GitInfo.

**Also shipping:** [adrenaline](https://github.com/M5Devs/adrenaline) — a modular Electron alternative
(WebView or pruned CEF, −32% peak RAM, drop-in API) · [ProDL](https://github.com/M5Devs/ProDL) —
Kotlin video downloader, 1000+ sites · [Total-Connect](https://github.com/M5Devs/Total-Connect) —
dual-pane file manager on rclone, 50+ providers in a TUI, web daemon or CLI ·
[FM-Infinite](https://github.com/M5Devs/FM-Infinite) — the first FM Towns emulator for Android ·
[RetroDJ](https://github.com/M5Devs/RetroDJ) — bare-metal chiptune tracker, pure register writes ·
[MikuBot-Discord](https://github.com/M5Devs/MikuBot-Discord) ·
[MikuBot-WhatsApp](https://github.com/M5Devs/MikuBot-WhatsApp) ·
[mikufetch](https://github.com/M5Devs/mikufetch). 40+ public repositories in total.

---

## 🎨 AI models

Nine public models at **[huggingface.co/M5-Dev](https://huggingface.co/M5-Dev)** — anime checkpoints,
character LoRAs and a voice-conversion net. Trained, documented, free to run on your own GPU.

| Model | Base | What it is | Pulls |
| :--- | :--- | :--- | ---: |
| [**MikuPix2**](https://huggingface.co/M5-Dev/MikuPix2) | SDXL 1.0 LoRA | Hatsune Miku character style — trigger `mikuPix2`, `hatsune miku`, `vocaloid`, `cyan hair`, `long twin tails` | 61 |
| [**MikuPixAI**](https://huggingface.co/M5-Dev/MikuPixAI) | SD 1.5 LoRA | Legacy Miku character LoRA for older A1111 and ComfyUI SD 1.5 pipelines | 58 |
| [**Miku_ME**](https://huggingface.co/M5-Dev/Miku_ME) | SDXL 1.0 finetune | Art and music finetune under CreativeML OpenRAIL-M | 33 |
| [**Miku-lora-for-sd-1.5**](https://huggingface.co/M5-Dev/Miku-lora-for-sd-1.5) | SD 1.5 LoRA | "Legacy edition" Miku LoRA tuned for Anything V5-class checkpoints | 32 |
| [**YumeXL**](https://huggingface.co/M5-Dev/YumeXL) | Illustrious-XL v1.0 | Anime checkpoint with a PixAI-trained LoRA merged into the weights | — |
| [**YumeXL-v1.5**](https://huggingface.co/M5-Dev/YumeXL-v1.5) | Pony Diffusion V6 XL | Pony-line counterpart to YumeXL, baked anime LoRA, standard SDXL checkpoint | — |
| [**Miku_RVC_Model**](https://huggingface.co/M5-Dev/Miku_RVC_Model) | RVC v2 | Miku voice conversion: 1000 epochs, 40/48 kHz, RMVPE pitch extractor. J-pop, future bass, ballads | — |

Also public: [MikuIllustrious1](https://huggingface.co/M5-Dev/MikuIllustrious1) (Miku LoRA for
Illustrious-XL v2.0) and [MSentara-Blender](https://huggingface.co/M5-Dev/MSentara-Blender).

<sub>Pulls are Hugging Face 30-day download counts, read 26 Nov 2026. An em dash means zero — we don't print empty numbers.</sub>

---

## 🕹️ The Nostalgia Archive

Dead platforms, kept alive. Mobile Java games, N-Gage prototypes and Flash — rebuilt file by file
from the Kahvibreak and Flashpoint preservation projects, so you can pull one game without pulling
a multi-gigabyte blob.

| Dataset | What's inside | Size | Pulls |
| :--- | :--- | :--- | ---: |
| [**j2me-vault**](https://huggingface.co/datasets/M5-Dev/j2me-vault) | **7,543 J2ME games**, file by file: Gameloft, EA Mobile, Konami, Sega, Namco, Capcom, Ubisoft, THQ, Digital Chocolate and SNK, plus delisted rarities (Silent Hill Mobile 1–3, Doom RPG) | 3.4 GB | 9,586 |
| [**j2me-full-romset**](https://huggingface.co/datasets/M5-Dev/j2me-full-romset) | **456 curated `.jar` games** plus **1,381 screenshots** from the M5 Nostalgia Archive | 303 MB + 153 MB | 1,410 |
| [**n-gage-romset**](https://huggingface.co/datasets/M5-Dev/n-gage-romset) | **70 N-Gage games**, including unreleased prototypes, plus 30 S60v3 `.n-gage` titles, BLZinstaller and cheats | 8 GB | 101 |
| [**webgtk-chromium-diet**](https://huggingface.co/datasets/M5-Dev/webgtk-chromium-diet) | Trimmed Chromium build behind the WebGTK webview | — | 104 |
| [**swf-vault**](https://huggingface.co/datasets/M5-Dev/swf-vault) | Flash SWF archive for Ruffle-era playback, companion to [ruffle-touch](https://github.com/M5Devs/ruffle-touch) | — | 27 |

Also public: MikuLoRA-Dataset.1-SFW (44) and .1-NSFW (15) training sets, and MSentara-Blender —
8 datasets in total.

---

## 🧰 Stack

![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

SDL2, Qt, LLVM, clang, ComfyUI and RVC where the job calls for it.

---

<div align="center">

**Built with rage & caffeine.** GPL. Forever free.

[Portfolio](https://M5Devs.github.io) · [GitHub](https://github.com/M5Devs) · [Hugging Face](https://huggingface.co/M5-Dev) · [X](https://x.com/M5Devs) · [Dev.to](https://dev.to/m5dev) · [YouTube](https://www.youtube.com/@m5devs) · [Discord](https://discord.gg/FYEjpcFYXc)

<sub>Cairo, Egypt 🇪🇬 · everything here is public</sub>

</div>
