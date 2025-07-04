

---

````markdown
# 📝 appwriteBlog

A full-featured blog web application built using **React**, **Appwrite**, and **Tailwind CSS**. It includes user authentication, post creation, editing, and a responsive UI — everything needed to launch a modern blog platform.

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
````

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
[GitHub](https://github.com/anuragsingh8076) • [Twitter](https://twitter.com/yourhandle) *(optional)*

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> Made with 💙 using React, Tailwind, and Appwrite

```


