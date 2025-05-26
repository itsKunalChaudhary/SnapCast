# 🎥 Snapcast - Screen Recording & Video Sharing Platform

**Snapcast** is a full-stack screen recording and video sharing web application built with cutting-edge technologies including **Next.js**, **Bunny.net**, **Xata**, and **Tailwind CSS**. It allows users to record their screens, upload and manage videos, generate AI-based transcripts, and securely share videos with powerful privacy and search features.

🌐 **Live App**: [snapcast-sooty.vercel.app](https://snapcast-sooty.vercel.app/)

---

## 🚀 Features

- 🔐 **Authentication**  
  Secure user login and registration using [Better Auth](https://betterauth.dev) and Google OAuth.

- 📺 **Screen Recording**  
  Record your screen directly within the browser—no extensions or installations required.

- 📤 **Video Uploading**  
  Upload videos seamlessly with support for both **public** and **private** visibility options.

- 🧠 **AI-Generated Transcripts**  
  Automatically generate searchable and accessible transcripts for uploaded videos.

- 🔒 **Privacy Controls**  
  Toggle video visibility between **public** and **private** modes.

- 🧰 **Security Integration with Arcjet**  
  Advanced bot protection, email validation, rate limiting, and form security powered by [Arcjet](https://arcjet.com).

- 📊 **Video Metadata**  
  View unique video IDs, URLs, and access detailed metadata for easy referencing.

- 🔎 **Search Functionality**  
  Intuitive search bar to locate your videos quickly and efficiently.

- 🔗 **Sharable Links**  
  Generate unique links to share videos securely with others.

- 💅 **Responsive Modern UI**  
  Clean and elegant UI/UX built with [Tailwind CSS](https://tailwindcss.com).

- 🗃️ **Database Integration**  
  Scalable real-time storage and management powered by [Xata](https://xata.io).

- ✅ **Type-Safe ORM**  
  Use [Drizzle ORM](https://orm.drizzle.team) for secure and type-safe SQL queries.

- 🌐 **Cross-Device Compatibility**  
  Fully responsive design ensures a seamless experience across all devices.

---

## 🧰 Tech Stack

| Category              | Technology        |
|-----------------------|-------------------|
| **Frontend**          | Next.js, TypeScript, Tailwind CSS |
| **Backend**           | Next.js API Routes |
| **Authentication**    | Better Auth, Google OAuth |
| **Database**          | Xata |
| **ORM**               | Drizzle ORM |
| **Video Delivery**    | Bunny.net |
| **Security**          | Arcjet |
| **Deployment**        | Vercel |

---

## 📁 Project Structure

````
/snapcast
│
├── /app # Next.js App Router
├── /components # Reusable UI components
├── /lib # Utility functions
├── /styles # Tailwind and global styles
├── /drizzle # Drizzle ORM config and schema
├── /public # Static assets
├── /types # TypeScript type definitions
└── .env # Environment variables
````


## 🧪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/itsKunalChaudhary/LoomClone.git
cd LoomClone

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env
# Fill in .env with your Xata, Bunny.net, Better Auth, and Arcjet credentials

# Run the development server
npm run dev
```
## 🛡️ Security

### Snapcast is integrated with Arcjet to ensure:

- Bot protection
- Rate limiting
- Email validation
- Attack protection on forms and login routes

## 📹 Powered By
- Bunny.net: For fast and secure video delivery.
- Better Auth: For scalable and flexible authentication.
- Xata: For real-time database storage and search.
- Drizzle ORM: For type-safe SQL operations.
- Arcjet: For developer-first security integration.
