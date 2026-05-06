# Prompt Generator Studio
### by Shared Frequency

> A standalone, no-install AI prompt generator for Meta AI, Stable Diffusion, and video models.  
> Built for consistent character production across multi-angle shot sequences.

---

## Quick Start

1. Download `SharedFrequency_PromptStudio_v1.0.html`
2. Open in any browser — Chrome, Firefox, Safari, Edge
3. Works completely offline. No server. No install.

---

## How It Works

Select your subject, lock your core DNA (seed + theme + lighting), then vary only the shot angle. Every render stays true to the same character.

```
Lock:   Seed · Theme · Lighting · Visual Style
Vary:   Shot Angle → Front Shot
        Generate → Copy → Render in Meta AI

Vary:   Shot Angle → Side Shot
        Generate → Copy → Render

Vary:   Shot Angle → Back Shot
        Generate → Copy → Render

Result: 3 angles. Same character. Every time.
```

---

## Lock System

Every field has a lock button. Two states only.

| State | Color | Behavior |
|-------|-------|----------|
| **Unlocked** | Green | Editable. The **[Random]** button WILL change it. |
| **Locked** | Red | Disabled. Nothing can change it — not even Random. |

**[Lock All]** in the sidebar locks everything at once.  
Click individual locks to release only what you need.

---

## Modes

| Mode | Use |
|------|-----|
| 🎨 **Image** | Full scene · subject · lighting · style · palette |
| 🎬 **Video** | All image fields + AI Role · Task · Format · Duration |

---

## Panels (in order)

1. **Subject** — Who or what is in the scene
2. **Scene** — Theme, time, weather, location
3. **Environment** — Details, background
4. **Video** *(Video mode only)* — Task, format, duration
5. **Lighting** — Style, sources, mood intensity
6. **Style & Quality** — Visual style, aesthetic, details
7. **Advanced** — Seed (DNA), aspect ratio, palette
8. **Negative Prompt** — What to exclude
9. **Output** — Generated prompt, editable

---

## Palette System

Select a palette from the **Advanced** panel. The full color definition — hex codes, accents, and vibe — is automatically injected into the generated prompt.

| Palette | Core Colors |
|---------|-------------|
| Synthwave | Hot Pink, Electric Purple, Neon Cyan |
| Cyberpunk | Neon Yellow, Electric Blue, Hot Pink |
| Vaporwave | Lavender, Soft Pink, Baby Blue |
| Steampunk | Rust Brown, Brass Gold, Copper |
| Dark Academia | Midnight Blue, Burgundy, Deep Gold |
| Bioluminescent | Electric Green, Cyan, Purple |
| Cottagecore | Sage Green, Dusty Rose, Cream |
| Noir | Black, Silver, Deep Blue + Red |

Use **[+]** to add your own custom palette.

---

## Shot Angle (Sidebar)

Located under **Output Mode** — change without touching any panel.

| Angle | Best For |
|-------|----------|
| Front Shot | Primary character reference |
| Side Shot | Profile / DNA consistency check |
| Back Shot | Full character coverage |
| Dutch Angle (Tilt) | Dynamic tension |
| Bird's Eye | Environment/scene overview |
| Macro Detail | Texture and detail focus |
| Low Angle | Power, scale, drama |
| Wide | Full scene context |
| Close Up | Emotion, face, detail |

---

## Export Filename

Files are named to be self-describing:

```
SF_IMAGE_chrome_robot_synthwave_front-shot_seed847263918_2026-05-06.txt
```

`SF_[MODE]_[SUBJECT]_[THEME]_[ANGLE]_seed[SEED]_[DATE].txt`

---

## Custom Dropdown Entries

Every dropdown has a **[+]** button. Type your value and click Add. It appears in the dropdown immediately and persists for the session.

---

## Character Library

| Action | How |
|--------|-----|
| Save | Click **[Save]** — enter a name |
| Load | Click any saved item in sidebar |
| Search | Type in the Search box |
| Filter | Select Image or Video from mode filter |
| Export | **[Export]** in sidebar — copies all saved prompts as JSON |
| Import | Paste JSON into sidebar — restores your full library |

---

## Responsive Design

| Device | Behavior |
|--------|----------|
| Desktop > 1024px | Full sidebar + panel grid |
| Tablet 768–1024px | Compressed sidebar + grid |
| Mobile ≤ 760px | ☰ hamburger opens sidebar drawer |

---

## Part of the Shared Frequency Toolkit

| Tool | Status |
|------|--------|
| **Kinetic Remix** | ✅ Live |
| **Prompt Generator Studio** | ✅ v1.0 |
| **Character DNA Studio** | 🔜 In development |

---

## License

MIT — see `LICENSE`.  
Free to use, modify, and distribute. Attribution appreciated.

---

*Built for the AI creative community by Shared Frequency.*
