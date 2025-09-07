# Toolkit.ai – Unified AI SaaS Platform

Toolkit.ai is a **SaaS platform** that unifies multiple **AI-powered tools** into a single application.  
It allows users to **generate blogs/articles, create images, remove objects/backgrounds, and analyze resumes** — all in one place.  

Secure login and subscription management is powered by **Clerk**, while **Firebase** handles media storage and **Neon** provides a serverless PostgreSQL database for seamless data management.  

---

## ✨ Features

- AI Blog & Article Generation – create high-quality content instantly.  
- AI Image Creation – generate creative images from text prompts.  
- Object/Background Removal – edit and enhance images effortlessly.  
- Resume Analyzer – AI-powered resume feedback & suggestions.  
- Community Dashboard – view shared prompts and uploaded creations.  
- Authentication & Payments – managed via Clerk.  
- Cloud Storage – Firebase for user uploads and assets.  
- Serverless DB – Neon PostgreSQL for scalability.  

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

```bash
# 1. Clone the Repository
git clone https://github.com/your-username/toolkit-ai.git
cd toolkit-ai

# 2. Install Dependencies
npm install

# 3. Setup Environment Variables
# Create a .env file in the root and add the following (replace placeholders with your keys):

DATABASE_URL=your_postgres_database_url

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

GEMINI_API_KEY=your_gemini_api_key
CLIPDROP_API_KEY=your_clipdrop_api_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

# ⚠️ Important: Never push .env to GitHub. Add it to .gitignore.

# 4. Run the App
npm run dev
