# 🔄 Complete AI Video Pipeline — Free Tools
> ครบทุก step โดยไม่มีค่าใช้จ่าย · No API key needed

---

## ⏱️ เวลาทั้งหมด: ~30-45 นาที

---

## 💡 STEP 1 — INFORMATION (5 นาที)

**กรอกข้อมูลนี้ก่อน:**

```
Concept:     ____________________________________
Platform:    [ ] TikTok 9:16  [ ] Reels 9:16  [ ] YouTube 16:9
Duration:    [ ] 12 seconds   [ ] 15 seconds
Style:       [ ] Cinematic  [ ] Dramatic  [ ] Viral  [ ] Calm
Mood:        ____________________________________
Character:   ____________________________________
Location:    ____________________________________
Message:     อยากให้คนดูรู้สึกอะไร? ____________________
```

---

## 📋 STEP 2 — STORYBOARD (10 นาที)

**เครื่องมือ:** [ChatGPT Free](https://chatgpt.com) — ไม่ต้องสมัคร Plus

1. เปิด ChatGPT
2. Copy template จาก `/prompts/openai/chatgpt-storyboard.md`
3. กรอกข้อมูลจาก Step 1
4. Paste ใน ChatGPT → กด Enter
5. Copy ตาราง storyboard ที่ได้

**ผลที่ได้:** ตาราง 4-5 shots พร้อม prompts ✅

---

## 🖼️ STEP 3 — STORYBOARD IMAGE (10 นาที)

**เครื่องมือฟรี (เลือกอย่างใดอย่างหนึ่ง):**

| Tool | Link | ข้อดี |
|------|------|-------|
| Adobe Firefly | [firefly.adobe.com](https://firefly.adobe.com) | ฟรี 25 credits/เดือน |
| Ideogram | [ideogram.ai](https://ideogram.ai) | ฟรี ไม่จำกัด |
| Microsoft Designer | [designer.microsoft.com](https://designer.microsoft.com) | ฟรี ใช้ DALL-E |
| **GPT Image 2** | [chatgpt.com](https://chatgpt.com) | **ดีที่สุด** (ต้องการ Plus) |

1. นำ AI prompt ของแต่ละ shot จาก Step 2
2. เพิ่ม **"photorealistic, 16:9, cinematic still"** ต่อท้าย
3. Generate ทีละ shot

**ผลที่ได้:** ภาพ reference สำหรับแต่ละ shot ✅

---

## 👤 STEP 4 — CHARACTER (5 นาที)

1. Copy template จาก `/characters/character-design-guide.md`
2. กรอกรายละเอียด character ของคุณ
3. ถ้าใช้ Cast Mode → เตรียมรูปหน้าตรง แสงดี

**เครื่องมือ:**
- [Dreamina](https://dreamina.capcut.com) → Cast Mode
- [Kling AI](https://kling.ai) → Character Reference

---

## 🎯 STEP 5 — FINAL PROMPT + VIDEO (10 นาที)

**นำทุกอย่างมารวม:**

```
[Character description] + [Shot type] + [Action] + 
[Location] + [Lighting] + [Camera movement] + [Style]
```

**ตัวอย่าง Final Prompt:**
```
Thai man in his 40s, glasses, dark jacket, walking slowly through 
neon-lit Bangkok street at night, heavy rain, wet pavement reflections, 
medium shot, slow camera push in, anamorphic lens flare, 
cinematic color grade, photorealistic, 8K
```

**Generate ที่:**
| Tool | Link | ฟรี? |
|------|------|------|
| Seedance 2.0 | [seedance.ai](https://seedance.ai) | ✅ Free tier |
| Kling AI | [kling.ai](https://kling.ai) | ✅ Free tier |
| Dreamina | [dreamina.capcut.com](https://dreamina.capcut.com) | ✅ Free tier |
| Hailuo | [hailuoai.video](https://hailuoai.video) | ✅ Free tier |

---

## 🔮 Coming Soon — With OpenAI API

> เมื่อได้รับ API credits จาก Codex for OSS Program:

- **Auto Storyboard** — กรอก concept → ระบบสร้าง storyboard ให้อัตโนมัติ
- **GPT Image 2 Integration** — generate storyboard frames ในเว็บได้เลย
- **Smart Prompt Builder** — UI เลือก style → ได้ final prompt ทันที

---

*Workflow by MyImage Studio — [facebook.com/MyImageStudio](https://facebook.com/MyImageStudio)*
