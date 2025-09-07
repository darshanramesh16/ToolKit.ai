# 🧰 Toolkit.ai – Unified AI SaaS Platform

Toolkit.ai is a **SaaS platform** that unifies multiple **AI-powered tools** into a single application.  
It allows users to **generate blogs/articles, create images, remove objects/backgrounds, and analyze resumes** — all in one place.  

Secure login and subscription management is powered by **Clerk**, while **Firebase** handles media storage and **Neon** provides a serverless PostgreSQL database for seamless data management.  

---

## ✨ Features

1. 📝 **AI Blog & Article Generation** – create high-quality content instantly.  
2. 🖼️ **AI Image Creation** – generate creative images from text prompts.  
3. 🎭 **Object/Background Removal** – edit and enhance images effortlessly.  
4. 📄 **Resume Analyzer** – AI-powered resume feedback & suggestions.  
5. 👥 **Community Dashboard** – view shared prompts and uploaded creations.  
6. 🔐 **Authentication & Payments** – managed via Clerk.  
7. ☁️ **Cloud Storage** – Firebase for user uploads and assets.  
8. 🗄️ **Serverless DB** – Neon PostgreSQL for scalability.  

---

## 🛠️ Tech Stack

**Frontend**
- React.js (Vite)  
- Tailwind CSS  

**Backend**
- Node.js + Express  
- PostgreSQL with DrizzleORM (Neon serverless)  

**Auth & Payments**
- Clerk  

**Cloud & APIs**
- Firebase (Image storage)  
- Gemini API (AI content generation)  
- ClipDrop API (Background/Object removal)  
- Cloudinary (Optional: media hosting)  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/toolkit-ai.git
cd toolkit-ai
