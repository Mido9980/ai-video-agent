# AI Video Agent — EASY CODE 🎬🤖

**وكيل الفيديو بالذكاء الاصطناعي — يعمل بكل اللغات**

A free, fully in-browser AI video agent. Write a short idea or paste a full script — it optimizes the prompt, builds a scene plan, generates a storyboard preview, and renders the final video with music. No API keys, no server, no cost.

## ✨ المميزات / Features

- 🌍 **يعمل بكل اللغات / Works in every language** — 14 built-in UI languages (العربية, English, Français, Español, Deutsch, Português, Türkçe, Русский, 中文, 日本語, हिन्दी, Indonesia, فارسی, اردو) with auto-detection, full RTL support, and native voiceover voices per language
- 🧠 **محسّن برومبت محلي مجاني** — deterministic local prompt optimizer (no LLM key needed)
- 🎞️ **خطة مشاهد + ستوري بورد** — scene plan with shots, captions, durations + storyboard contact sheet
- 🎥 **توليد فيديو داخل المتصفح** — Canvas + MediaRecorder + WebAudio music, 100% free
- ⚙️ **إعدادات كاملة** — duration, resolution (720p → 4K), frame rate, voice, music mood
- 💬 **محادثات محفوظة** — chats stored in localStorage
- 🖥️ **وضع خادم اختياري** — connect a FastAPI + FFmpeg backend for multi-user, long-form rendering (edge-tts voices)

## 🚀 التشغيل / Run

Just open `index.html` in any modern browser. That's it — everything runs locally.

Optional server mode: connect your FFmpeg backend URL from the Account screen.

## 🗂️ بنية المشروع / Structure

```
index.html   ← the whole app (single file, no dependencies)
```

## 🧰 التقنيات / Tech

Vanilla JS · Canvas 2D · WebAudio · MediaRecorder · localStorage — zero dependencies, zero build step.

## 📄 License

MIT — free for personal and commercial use.

---

Made with ❤️ under the **EASY CODE** brand — *Apps Made Easy*
