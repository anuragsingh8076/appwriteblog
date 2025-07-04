# 📝 appwriteBlog

A full-featured blog web application built using **React**, **Appwrite**, and **Tailwind CSS**. It includes user authentication, post creation, editing, and a responsive UI — everything needed to launch a modern blog platform.

🌍 **Live Demo**: [https://appwriteblog-seven-liart.vercel.app](https://appwriteblog-seven-liart.vercel.app)

---

## 🚀 Features

- 🔐 User authentication (Signup, Login, Logout)
- 📝 Create, edit, and delete blog posts
- 🖼️ Rich Text Editor for blog content
- 🗂️ Appwrite Database integration
- 📁 File upload support via Appwrite Storage
- 🌐 Public and private routes
- 🎨 Fully responsive UI with Tailwind CSS
- ⚙️ State management using Redux Toolkit

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **Backend Services**: Appwrite (Auth, Database, Storage)
- **State Management**: Redux Toolkit
- **Form Handling**: react-hook-form
- **Routing**: react-router-dom

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/anuragsingh8076/appwriteblog.git
cd appwriteblog
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Appwrite

* Create a project in [Appwrite](https://appwrite.io/)
* Set up:

  * **Authentication**
  * **Database** (with collections for posts and users)
  * **Storage** (for images or file uploads)

* Create an `.env` file:

```env
VITE_APPWRITE_ENDPOINT=your-appwrite-endpoint
VITE_APPWRITE_PROJECT_ID=your-project-id
VITE_APPWRITE_DATABASE_ID=your-database-id
VITE_APPWRITE_COLLECTION_ID=your-collection-id
VITE_APPWRITE_BUCKET_ID=your-bucket-id
```

### 4. Run the Development Server

```bash
npm run dev
```

---

## ☁️ Deploy on Vercel

You can easily deploy this project to [Vercel](https://vercel.com/) with the following steps:

1. **Push your code to GitHub**
2. **Go to [vercel.com](https://vercel.com/)** and connect your GitHub account
3. **Import your repository** and configure environment variables in the Vercel dashboard:

   - `VITE_APPWRITE_ENDPOINT`
   - `VITE_APPWRITE_PROJECT_ID`
   - `VITE_APPWRITE_DATABASE_ID`
   - `VITE_APPWRITE_COLLECTION_ID`
   - `VITE_APPWRITE_BUCKET_ID`

4. **Deploy!** Vercel will handle the rest and give you a live URL.

✅ **Deployed URL**: [https://appwriteblog-seven-liart.vercel.app](https://appwriteblog-seven-liart.vercel.app)

---

## 📁 Folder Structure

```
appwriteblog/
├── public/
├── src/
│   ├── appwrite/         # Appwrite configuration & services
│   ├── components/       # Reusable UI components
│   ├── pages/            # Main app pages (Home, Login, Signup, etc.)
│   ├── store/            # Redux slices and store setup
│   ├── conf/             # Config files
│   ├── App.jsx           # Main component
│   └── main.jsx          # App entry point
├── .env.sample           # Sample env file
├── tailwind.config.js    # Tailwind CSS config
├── vite.config.js        # Vite config
└── package.json
```

---

## 👨‍💻 Author

**Anurag Singh**  
[GitHub](https://github.com/anuragsingh8076) • [Twitter](https://x.com/Singh8076Anurag)

> Made with 💙 using React, Tailwind, and Appwrite




