<p align="center">
  <a href="#pjsekai-overlay-append--forked-pjsekai-style-video-creation-tool"><strong>English Section</strong></a> | <a href="#pjsekai-overlay-append--フォークプロセカ風動画作成補助ツール"><strong>日本語セクション</strong></a>
</p>

<p align="center">
  <a href="https://github.com/TootieJin/pjsekai-overlay-APPEND/blob/main/LICENSE"><img src="https://img.shields.io/github/license/TootieJin/pjsekai-overlay-APPEND" alt="License"></a> 
  <a href="https://github.com/TootieJin/pjsekai-overlay-APPEND/releases/"><img src="https://img.shields.io/github/downloads/TootieJin/pjsekai-overlay-APPEND/total" alt="Releases"></a> 
  <a href="https://github.com/TootieJin/pjsekai-overlay-APPEND/stargazers"><img src="https://img.shields.io/github/stars/TootieJin/pjsekai-overlay-APPEND?style=flat&amp;color=yellow" alt="Stargazers"></a>
</p>

# rhythmhive-overlay-SONO / Forked Rhythm Hive-style video creation tool

[![pjsekai-overlay-APPEND thumbnail](https://github.com/user-attachments/assets/dcc037f7-1c2b-4b83-b17b-b3c5155d670c)]()

Fork of [pjsekai-overlay](https://github.com/sevenc-nanashi/pjsekai-overlay) by [TootieJin](https://tootiejin.com), an open-sourced tool to make Project Sekai Fanmade (custom chart) videos - in other words... "Make your Sonolus look like Project Sekai."

> [!CAUTION]
> **Before using pjsekai-overlay-APPEND:** This tool is primary only for people with **technical know-how and basic knowledge of AviUtl.** \
> Only use this tool if you can figure it out yourself. If problems arise, **please [make a discussion thread.](https://github.com/TootieJin/pjsekai-overlay-APPEND/discussions)** \
> Please also read the [Terms of Use](#terms-of-use) after using the tool.
> 
> - *P.S. To [a certain someone](https://discordid.netlify.app/?id=1370076899404939327) (a.k.a [this person](https://discordid.netlify.app/?id=919036186473947187)) with the mindset of `"Just switch to a different editing software since I don’t even know how to install aviutl"` [(image source)](https://github.com/user-attachments/assets/4850442d-3f3a-438a-92d9-97d052f2fba0): I suggest you **make your own pjsekai-overlay that supports your desired editing software.** (if you can even find a video editor that is as versatile and extensible as AviUtl, that is).*

This is a forked version of pjsekai-overlay-append with additional features originally not in the main repo, including:
- **AviUtl ExEdit2 Full Support**
- [Extra assets](./extra-assets)
- Added/adjusted elements to look identical to the official photography
- Quickly make 1080p videos
- iPad (4:3) video support
- Ability to use the English AviUtl
- v1 UI skin (Full support)
- Automatically changes chart difficulty to generate in AviUtl based on chart tag (or title)
- **(AviUtl ExEdit2 ONLY)** Supports very big number (~ 1.7e+307) using [lua-bignumber](https://github.com/thenumbernine/lua-bignumber)
- **[Various UI customization](https://github.com/TootieJin/pjsekai-overlay-APPEND/wiki/Start-Here!#ui-customization-specifications)**
  - Animated Scoring
  - Adjust animation speed in different elements
  - Interchangable AP Combo
  - Interchangable judgement type (PERFECT/GREAT/GOOD/etc.)
  - Interchangable LIFE value
  - Skill Effects (v1 + v3)
  - Achievement Rate
