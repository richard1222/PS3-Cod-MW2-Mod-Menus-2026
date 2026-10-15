# Call of Duty: Modern Warfare 2 (PS3) — Definitive Mod Menu Guide

**Compiled 2026-10-09. Read-only research: web search + page text, no accounts, no downloads, no posts.**

---

## 0. Read this first — the 1.11 vs 1.14 situation

MW2 on PS3 (2009, IW4 engine) received title updates up to **1.14 — that is the final official update**, not 1.11. Patch **1.11** (March 8, 2011, announced by IW's Robert "fourzerotwo" Bowling) was a famous **security update** that addressed the post-PS3-key-leak hacking epidemic and fixed a Fuel map exploit. Further updates (1.12/1.13/1.14) followed.

Why it matters: **a modded `patch_mp.ff` must match the installed title update.** A 1.11-built patch will not work on a 1.14 install and vice versa (menu won't open / black screen). Most classic GSC menus were built for 1.11, because 1.14 closed the patch-loading path those menus relied on.

**The 2026 revival:** jacob-schroeder's **[IW4-Binaries](https://github.com/jacob-schroeder/IW4-Binaries)** — a modified TU 1.14 `default_mp.self` (v2.4.2) with native `.gsc` parsing/linking/compilation, a mod loader (`mods/` folder), region-unlocked fastfiles, security fixes, and fixed matchmaking. It lets **1.11-era `patch_mp.ff` menus load on 1.14 with NO bypass and WITH online play**, on CFW **and** HEN (separate builds per region). As of late 2026, the active scene runs **1.14 + IW4-Binaries** loading the old classics.

---

## 1. Title IDs (verified)

| Region | Title ID |
|---|---|
| MW2 EU | **BLES00680** |
| MW2 US | **BLUS30408** |

Note: BLES00683 / BLUS30377 sometimes appear in old download lists — those are **MW3** IDs, not MW2. Use BLES00680 / BLUS30408.

---

## 2. Menu catalog (every entry has a link or explicit status)

Legend: ✅ public/live · 🔒 login-gated (downloads hidden without account) · ⚠️ link status uncertain · ❓ unverified (no public trace found)

### EliteMossy family (1.11 era)

| Menu | Creator | What it is | Patch | Link |
|---|---|---|---|---|
| EliteMossy v1–v11, PvT v1/v2, DT v8–v11 | EliteMossy | MP mod menu + infections, prestige/rank/challenge lobbies | 1.11 | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/573519-all-111-mw2-mod-menus-2.html |
| EliteMossy's Private Patch v2 ("my last ever MW2 patch", 302 options) | EliteMossy | MP mod menu — model menu, infections, bots, stats, gamemodes | 1.11 | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/324604-elitemossys-private-patch-v2-my-last-ever-mw2-patch-22.html |
| RedDotCity v6–v6.8, PvT v2 | RedDotCity | Infectable MP mod menu | 1.11 | 🔒 NGU "All 1.11 Mw2 Mod Menu's" (same thread as above) |
| Blackrain v8.20 / v2.1–v2.5 | JokerRey | MP mod menu | 1.11 | 🔒 NGU "All 1.11 Mw2 Mod Menu's" (same thread as above) |

### WhiteWater family

| Menu | Creator | What it is | Patch | Link |
|---|---|---|---|---|
| WhiteWater v4.0 "Ultimate Patch" | JokerRey, xRobertDavisx, HepticOnline (built on Blackstorm's edit of DEREKTROTTER's patch) | MP mod menu + 7 bundled patches + ~30 gamemodes; prestige/stats/weapons menus | 1.11 ("This Is A 1.11 Patch — Still Works On Bypass") | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/583570-whitewater-v40-ultimate-patch-updating-8.html |
| WhiteWater v5 | WhiteWater team (RMG era) | MP mod menu, 1.14-compatible release | 1.14 NO BYPASS | ⚠️ MediaFire via video: https://www.youtube.com/watch?v=tnXz2ovjd_U |

### 1.14-era / modern releases

| Menu | Creator | What it is | Patch | Compat | Link |
|---|---|---|---|---|---|
| Restxrt's Private Patch v1 | Restxrt Modz | MP mod menu (host menu, gamemodes, infections) | 1.14 NO BYPASS | CFW/HEN | ⚠️ MediaFire in video description: https://www.youtube.com/watch?v=z4ThoBnU7is |
| OdysseyModz V1 | OdysseyModz | 1.14 patch: name changer, keyboard menu, 13+ aimbots, customizable colors, stable non-host | 1.14 | CFW | 🔒 CabConModding: https://cabconmodding.com/threads/odysseymodz-v1-patch-mw2-1-14-ps3.3078/ |
| Stimulus v1.1 (SPRX) | showcased by RawModz | SPRX mod menu, host + non-host/pre-game | 1.14 | CFW/HEN | ⚠️ YouTube + MediaFire: https://www.youtube.com/watch?v=5CuhB4Glwew |
| IW4-Binaries (GSC patch loader) | jacob-schroeder (Jakes625) | Modified 1.14 `default_mp.self` — THE enabler: native GSC support, mod loader, online play | 1.14 (TU 1.14 v2.4.2) | CFW/HEN | ✅ GitHub: https://github.com/jacob-schroeder/IW4-Binaries |

### Other verified menus

| Menu | Creator | What it is | Patch | Link |
|---|---|---|---|---|
| The Gamemode Patch v1/v2 | xxKILLALLMW2xx | 37+ gamemodes (hide & seek, gun game, AI zombies, Zombieland, COD4 mode, Big XP lobby), challenge lobby | [1.11] | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/595375-the-gamemode-patch-v1-xxkillallmw2xx-111a-4.html |
| R3FL3X V2 GSC Mod Menu | xePixTvx | MP GSC mod menu | 1.11 | 🔒 CabConModding: https://cabconmodding.com/threads/call-of-duty-modern-warfare-2-r3fl3x-v2-gsc-mod-menu-by-xepixtvx-download.1929/ |
| Project HD | xGscClan/xGscModz | MP mod menu (unfinished/buggy release) | 1.11-era | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/594435-project-hd-xgscclan-1.html |
| ThatGuyKalvin's MW2 modded patch | ThatGuyKalvin | Modded `patch_mp.ff` binary | era (2015, unstated) | ✅ GitHub: https://github.com/ThatGuyKalvin/mw2-patch_mp.ff |
| Blackstorm's Menu System v3 | Blackstorm | Menu system/codebase used as base in many patches (incl. WhiteWater) — **GSC source posted in thread** | [1.11] | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/451689-111-release-blackstorms-menu-system-v3a-2.html |
| xChronicModz v4.1.0 | xChronicModz | MP patch, aimbot focus, force host, infections | 1.12 | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/409413-release-new-xchronicmodz-v410-mw2-112-patch-11.html |
| NicoBvB90 1.13 Privat | NicoBvB90 | Private patch, infectable menu | 1.13 | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/546846-nicobvb90-113-privat-2.html |
| Stealth patch (non-host aim assist + menu) | woofdawg233 / Tacotime77 | Non-host stealth patch + menu, v1–v8 | 1.11-era | 🔒 NGU: https://nextgenupdate.com/forums/call-duty-modern-warfare-2/329020-stealth-patch-non-host-aim-assist-menu-edit-2.html |

### SPRX menus (native-code plugins — see §6)

Known names from the Se7enSins mega-collection and release threads: **Atlantic** (EternalModz — ✅ source: https://github.com/EternalModz/AtlanticMW2-SPRX-V2, 1.14), **Paradise** (MW2 ParadiseSPRX), **Black Ice v1/v2** (BlackIce_V2_SPRX), **Resurrection** (MW2_Resurrection_SPRX), **Insidious / Insidious V2**, **Parallax / Parallax Remastered**, **Superman v1/v2/v3**, **Fury V2**, **MARSHAL V1**, **Hestia**, **Cotton Candy**, **Elite Bot Final** (aimbot/ESP, **DEX-only**), **MW2-OB-SPRX**, **Matrix (Azza)**, **RCE Blue/Purple**, **ASP Engine**, **Insanity_V1_Non**, **ParadoxMW2**, **ZeroTwo**, **Zircon v1.5**, **Teh1337 (1.14)**, **Project Eva**, **Project Nightmare**, **Synergy (offhost)**.

Collection hub: ✅ https://www.se7ensins.com/forums/threads/release-ultimate-playstation-3-ps3-mod-menu-package-tools-mega-collection.1931291/ (most individual downloads login-walled or on dead file hosts — availability unverified per menu)

### Corrections — names that did NOT check out

- **Jiggy V2/V3/V4 "for MW2"** — no public trace. The famous Jiggy v4.x releases are **Black Ops 2** menus, not MW2.
- **Project Reborn / Reborn HD** — no trace under this name; likely "Project Reloaded" (vampehtwist) or "Project HD" misremembered.
- **iCONCUSS / Concuss** — no verified MW2 PS3 release thread found.
- **TWD (The Walking Dead) patch** — only a suspicious 751.9 MB MediaFire mirror (https://www.mediafire.com/file/ebk9swbayhasaff/TWD113.rar/file); far too big for a patch, treat with caution.
- **xModz HD, ApocZz V3, NextGen v4/v5, Matrix v3, Envy v3, SlickWilly v2.3, K Brizzles, xAzt3c v9, Swaqqin v1, Dark Matter v2, Virus/Requiem v4, Chaos Masta V10, Exotic v3, Insanity V3/V4, Toxic v3, xC4 v1.2, xVengeance, xXxR3GUL4RxXx v2, Extinct V2, Fusion V4, Illuminati v2, Legacy v1** — no public traces; likely buried in login-gated NGU history. A live NGU session would be needed to confirm them.

---

## 3. 1.11 vs 1.14 — detailed comparison

| | Patch 1.11 | Patch 1.14 |
|---|---|---|
| Status | March 8, 2011 security update | **Final official title update** (2011) |
| Classic GSC menus | ✅ Native — most golden-age menus built for it | ❌ 1.11 patches don't load (menu won't open / black screen) |
| Modern 1.14 menus | ❌ Don't work | ✅ Native (WhiteWater v5, Restxrt, OdysseyModz, SPRX builds) |
| Online play (2026) | Only via bypass (offline/private) | ✅ Full online with IW4-Binaries |
| What most players use today | Legacy setups | **1.14 + jacob-schroeder's patched `default_mp.self`** |

**Can a 1.11 menu work on 1.14?** Not directly. Old method: "bypass" (delete/replace `default_mp.self` to force 1.11) — works but kills online matchmaking. Modern method: install IW4-Binaries' modified 1.14 `default_mp.self` — 1.11-era `patch_mp.ff` menus then load on 1.14 with no bypass and online works.

**Downgrading 1.14 → 1.11:** XMB → Game → Game Data Utility → delete the MW2 update entry → install the 1.11 TU PKG (region-matched) → replace `patch_mp.ff` with a 1.11 menu. (The PKG installer refuses if a newer update is present, so deletion first is mandatory.)

**How to check your installed MW2 patch version:** XMB → Game → **Game Data Utility** → the MW2 update entry shows its version. The in-game multiplayer menu also displays it.

---

## 4. Installation (PS3)

### Classic GSC menus (patch_mp.ff replacement)
1. Jailbreak/HEN PS3 with a file manager (multiMAN) or FTP (Blackbox FTP + FileZilla).
2. Go to `/dev_hdd0/game/<TITLE_ID>/USRDIR/` — **BLES00680** (EU) or **BLUS30408** (US).
3. Back up the original `patch_mp.ff`, replace with the modded one (region + patch version must match).
4. Boot MW2 → multiplayer. (D-pad up usually opens the menu; varies per patch.)

### Modern 1.14 method (recommended, 2026)
1. From [IW4-Binaries releases](https://github.com/jacob-schroeder/IW4-Binaries), download the `default_mp.self` matching your **region** and **CFW or HEN** build.
2. Place it in the game update dir: `/dev_hdd0/game/{region}/usdir/default_mp.self`.
3. Drop any 1.11-era `patch_mp.ff` menu alongside it — no bypass needed, online works.

### SPRX menus
- Load via a plugin loader: **webMAN MOD** (`/dev_hdd0/boot_plugins.txt`), **PS3HEN plugin system**, or **CCAPI 2.80** (`/dev_usb000/plugins/`, CFW only, 4.21–4.55 era). Some ship a modded EBOOT (drop SPRX in `/dev_hdd0/tmp/`, EBOOT in the MW2 game dir).
- nas927/modmenups3 (https://github.com/nas927/modmenups3) is an open-source SPRX/VSH-menu loader (CEX/DEX/HEN).

---

## 5. CFW vs HEN

- **CFW:** everything works — patch_mp.ff replacement, SPRX via CCAPI/TMAPI/webMAN, IW4-Binaries CFW builds. Firmware-agnostic (3.55 through 4.9x); DEX vs CEX matters only for TMAPI (DEX-only) and some DEX-only SPRX menus (e.g. Elite Bot).
- **HEN:** patch_mp.ff replacement works the same (needs only file write access). SPRX loading works via webMAN MOD / HEN plugin system (`boot_plugins.txt`) — **not** via CCAPI. 2026-era releases (IW4-Binaries, Restxrt, WhiteWater v5, Stimulus SPRX) are explicitly labeled **CFW/HEN** with separate HEN builds where needed.
- Bottom line: on modern HEN you can run the full 1.14 stack (IW4-Binaries HEN build + classic patches + HEN-loaded SPRX).

---

## 6. SPRX menus — how they differ from patch_mp.ff

| | SPRX (native) | patch_mp.ff (GSC) |
|---|---|---|
| Language | C/C++, PS3 SDK | GSC script |
| Capability | Aimbot, ESP, non-host/offhost features, memory hooks | Script-level mods (god mode, UFO, infections, dvar tweaks); mostly host-dependent |
| Build skill | High (SDK, offsets, PPC) | Medium (GSC + FF tools) |
| Title-update sensitivity | **Very** — hardcoded memory offsets shift per TU (releases tagged 1.11 vs 1.14, e.g. "Teh1337_On_1.14") | High — FF must match installed TU |
| Loading | Needs a loader (CCAPI/TMAPI/webMAN/HEN plugins) or modded EBOOT | Just replace `patch_mp.ff` |
| Best for | Feature-rich all-client menus, RTE tools | Quick menu ports, GSC experimentation |

Known MW2 SPRX menus: Atlantic (EternalModz, 1.14, source on GitHub), Paradise, Black Ice v1/v2, Resurrection, Insidious/V2, Parallax/Remastered, Superman v1–v3, Fury V2, MARSHAL V1, Hestia, Cotton Candy, Elite Bot Final (**DEX-only**), MW2-OB, Matrix (Azza), RCE Blue/Purple, ASP Engine, ZeroTwo, Zircon v1.5, Project Eva/Nightmare, Synergy (offhost). Hub: the Se7enSins mega-collection thread (link in §2).

---

## 7. Build tools (MW2 PS3)

- **[CoD-FF-Tools](https://github.com/primetime43/CoD-FF-Tools)** (v4.0.0, active 2026) — MW2 **PS3 = Full support** (decompress, edit all asset types, recompress). Same GUI workflow as the WaW work (editor, compiler, converter, extractor, `ffcli` CLI). MW2 PS3 asset IDs: `menufile 0x19`, `localize 0x1A`, `weapon 0x1B`, `rawfile 0x23`, `stringtable 0x24`. Saves are unsigned (fine on CFW/HEN).
- **MW2 PS3 `patch_mp.ff` format notes:** MW2 console zone headers are 16/20-byte big-endian; PS3 raw files carry a 16-byte header + zlib data; multi-zlib-stream layout; signed retail files use IW4 "authed chunks" at offset `0x25`. (The exact FF version constant, e.g. 0x1D6, was not independently confirmed — check `MW2GameDefinition.cs` in CoD-FF-Tools.)
- **Historical:** BuC-ShoTz's PS3 FastFile Editor (NGU preview thread; EliteMossy himself thanked the post), aerosoul94's FF Viewer (MW2 support planned but never finished — treat as historical).
- **Modern GSC path:** IW4-Binaries adds **native `.gsc` parsing, linking and compilation** plus a `mods/` folder loader — effectively removes the FF-repacking step for GSC work on 1.14.
- IW4 vs WaW GSC: same CoDScript base, different built-in function sets per engine; scripts aren't portable between engines. No authoritative IW4-vs-WaW diff source found.

---

## 8. Sources

- NextGenUpdate — MW2 Mods/Patches/Tutorials + PS3 Mods Q&A (login-gated downloads; thread titles/snippets used)
- Se7enSins — [Ultimate PS3 Mod Menu Mega Collection](https://www.se7ensins.com/forums/threads/release-ultimate-playstation-3-ps3-mod-menu-package-tools-mega-collection.1931291/)
- CabConModding — MW2 section (index 403'd to text fetcher; thread pages via search snippets)
- PSX-Place, Reddit r/ps3homebrew, ConsoleCrunch, MPGH
- GitHub: [jacob-schroeder/IW4-Binaries](https://github.com/jacob-schroeder/IW4-Binaries) · [EternalModz/AtlanticMW2-SPRX-V2](https://github.com/EternalModz/AtlanticMW2-SPRX-V2) · [primetime43/CoD-FF-Tools](https://github.com/primetime43/CoD-FF-Tools) · [ThatGuyKalvin/mw2-patch_mp.ff](https://github.com/ThatGuyKalvin/mw2-patch_mp.ff) · [nas927/modmenups3](https://github.com/nas927/modmenups3) · [setsid/ps3-tools](https://github.com/setsid/ps3-tools)
- YouTube: RawModz / RMG (1.14 NO BYPASS showcases), Virus Mike
- consolemods.org — [PS3:Modding PS3 Games](https://consolemods.org/wiki/PS3:Modding_PS3_Games) (EBOOT/SPRX install paths)
- Archive.org — thin coverage; no dedicated MW2 PS3 patch items found. Brewology — no MW2 menus hosted.

## 9. Gaps / unverified

1. Exact FF version constant for MW2 PS3 (e.g. 0x1D6) — check `MW2GameDefinition.cs`.
2. Release date/changelog of TU 1.14 (and 1.12/1.13) beyond "postdates March 2011".
3. Patch version of ThatGuyKalvin's `patch_mp.ff` (2015, unstated).
4. ~18 menu names from the request list with no public trace (see §2 corrections) — likely login-gated NGU history; needs a live NGU session.
5. Per-menu download availability for most SPRX menus (login-walled/dead hosts).
6. Detailed IW4-vs-WaW GSC scripting differences (no authoritative source).

---

## Join Our Discord

- **Discord:** unosdopplegange
- **Discord server:** https://discord.gg/MDcaC5nPuA
