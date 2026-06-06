# 🎬 AI Video Creator Tool

> End-to-end AI video creation pipeline — from concept to final prompt.  
> Powered by OpenAI GPT Image 2 · Built for Thai & Southeast Asian creators.

[![Facebook](https://img.shields.io/badge/Facebook-48K%20Followers-blue?logo=facebook)](https://facebook.com/MyImageStudio)
[![Community](https://img.shields.io/badge/SD%20Thailand-67.6K%20Members-orange)](https://facebook.com/groups/stablediffusionthailand)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Website](https://img.shields.io/badge/Website-Live-brightgreen)](https://v0-myimage-studio-website.vercel.app)

---

## 🌏 What is This?

**AI Video Creator Tool** is a free, open-source pipeline tool that guides creators through every step of AI video production — from raw idea to ready-to-use prompts.

Most AI video guides are in English. This project serves the **~115,000 Thai/SEA AI creators** in our community who need practical, tested, and localized resources.

---

## 🗺️ The 5-Step Pipeline

```
💡 STEP 1: INFORMATION
   Enter your concept, style, mood, and target platform
            ↓
📋 STEP 2: STORYBOARD
   AI generates shot-by-shot breakdown (12s or 15s format)
   Tool: ChatGPT Free → use our ready-made prompt templates
            ↓
🖼️ STEP 3: STORYBOARD IMAGE
   Generate visual reference for each shot
   Tool: GPT Image 2 (ChatGPT Plus) → coming soon via API
            ↓
👤 STEP 4: CHARACTER
   Design and describe your character for Cast Mode
   Tool: Dreamina Cast Mode / Kling Character Reference
            ↓
🎯 STEP 5: FINAL PROMPT
   Get optimized, ready-to-use prompts for your video platform
   Tool: Seedance 2.0 / Kling / Dreamina / Sora
```

---

## 🛠️ Tools Integrated

### OpenAI (Primary)
| Tool | Step | Usage |
|------|------|-------|
| **ChatGPT (Free)** | Step 1–2 | Concept development + Storyboard generation |
| **GPT Image 2** | Step 3 | Visual storyboard frame generation |
| **Sora** | Step 5 | AI video generation |
| **Codex** | Dev | Powers the interactive tool builder |

### AI Video Platforms
| Tool | Step | Usage |
|------|------|-------|
| **Seedance 2.0** | Step 5 | High-quality video generation |
| **Dreamina** | Step 4–5 | Cast Mode + video generation |
| **Kling AI** | Step 4–5 | Character reference + video |
| **Wan 2.1** | Step 5 | Open-source video model |
| **Hailuo** | Step 5 | Fast video generation |

---

## 🗂️ Repository Structure

```
ai-video-creator-tool/
├── README.md
├── prompts/
│   ├── openai/
│   │   ├── gpt-image-prompts.md        # GPT Image 2 reference prompts
│   │   ├── sora-video-prompts.md       # Sora video prompts
│   │   └── chatgpt-storyboard.md       # ChatGPT storyboard templates
│   ├── seedance/
│   │   └── seedance-prompts.md         # Seedance 2.0 optimized prompts
│   ├── kling/
│   │   └── kling-prompts.md
│   └── dreamina/
│       └── dreamina-cast-prompts.md
├── storyboards/
│   ├── tiktok-12s-template.md          # 12-second TikTok template
│   ├── reels-15s-template.md           # 15-second Reels template
│   └── cinematic-template.md           # Cinematic style template
├── characters/
│   ├── character-design-guide.md       # Character description guide
│   └── cast-mode-prompts.md            # Cast Mode prompt templates
├── workflows/
│   ├── full-pipeline-free.md           # Complete workflow (free tools)
│   └── full-pipeline-openai.md         # Complete workflow (OpenAI tools)
└── examples/
    └── sample-projects.md              # Example completed projects
```

---

## 🚀 Roadmap

### ✅ Phase 1 — Now (Static Library)
- Prompt templates for all major AI video tools
- Storyboard templates (12s/15s)
- Step-by-step workflow guides
- Bilingual Thai/English documentation

### 🔄 Phase 2 — With ChatGPT Pro + Codex
- **Interactive Storyboard Generator** — input concept → auto-generate shot breakdown
- **Prompt Builder UI** — select style/mood → get optimized final prompt
- **Character Prompt Generator** — describe character → get Cast Mode prompt

### 🔮 Phase 3 — With API Credits
- **GPT Image 2 Integration** — auto-generate storyboard frame images
- **Full Interactive Pipeline** — complete 5-step tool in one web interface
- **Thai Language Support** — full UI and prompts in Thai

---

## 🤝 Community

| Platform | Size | Role |
|----------|------|------|
| [MyImage Studio](https://facebook.com/MyImageStudio) | 48,000+ followers | Owner |
| [Stable Diffusion Thailand](https://facebook.com/groups/stablediffusionthailand) | 67,600+ members | Admin |
| **Total Reach** | **~115,000 creators** | Thai/SEA AI Community |

---

## 💡 How to Use (Free — No API Key Needed)

### Step 1 — Get Your Storyboard
1. Open [ChatGPT Free](https://chatgpt.com)
2. Copy the template from `/prompts/openai/chatgpt-storyboard.md`
3. Fill in your concept and paste into ChatGPT

### Step 2 — Generate Reference Images
1. Open [ChatGPT Plus](https://chatgpt.com) or [Adobe Firefly](https://firefly.adobe.com) (free)
2. Use prompts from `/prompts/openai/gpt-image-prompts.md`

### Step 3 — Generate Your Video
1. Copy your final prompt from Step 1
2. Go to [Seedance 2.0](https://seedance.ai) / [Kling](https://kling.ai) / [Dreamina](https://dreamina.capcut.com)
3. Paste and generate!

---

## 🤲 Contributing

All contributions welcome — add prompts, templates, or workflows!

1. Fork this repository
2. Add your content to the appropriate folder
3. Submit a Pull Request

---

## 📄 License

MIT License — Free to use, share, and contribute.

---

*Built with ❤️ for the Thai and Southeast Asian AI creator community.*  
*[facebook.com/MyImageStudio](https://facebook.com/MyImageStudio)*
