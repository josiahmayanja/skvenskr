# skvenskr 🇸🇪  
**A modern Swedish writing assistant — fast, clear, no fluff.**

---

## 🚀 What is skvenskr?

skvenskr helps Swedish speakers and learners write better Swedish.  
It checks grammar and spelling using smart language tools and explains issues in simple, clear language.

- ✅ Paste Swedish text  
- ✅ Click “Check”  
- ✅ See grammar issues  
- ✅ Apply clean, confident fixes  
- ✅ Get human-style explanations (optional)

---

## 🧱 Tech Stack

**Frontend:**  
- React + TypeScript  
- Tailwind CSS  

**Backend:**  
- Node.js + Express (TypeScript)  
- LanguageTool API (grammar + spelling)  
- OpenAI GPT-4 Turbo (explanations only, optional)

**Hosting:**  
- Vercel (frontend)  
- Render or Railway (backend)

---

## 🗂️ Project Structure

### `/frontend`
> React + TypeScript

- Text input box for Swedish
- “Check Text” button
- Displays grammar suggestions and fixes
- Clean UI with Tailwind CSS

### `/backend`
> Node.js + Express (TypeScript)

- `/check` endpoint (POST)
- Sends text to LanguageTool
- Formats grammar suggestions
- Optionally adds GPT explanation (only when needed)

