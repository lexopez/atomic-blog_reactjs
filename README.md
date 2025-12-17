# ⚛️ The Atomic Blog

The Atomic Blog is a fast, lightweight React application designed to demonstrate efficient state management and component composition. It allows users to create, search, and manage blog posts in real-time.

## 🚀 Features

- **Real-time Search**: Instantly filter through posts using the search bar.
- **Post Management**: Easily add new "atomic" posts or clear the entire feed.
- **Dynamic Stats**: A live counter that tracks the number of posts found.
- **Dark Mode Support**: Built-in toggle for a comfortable viewing experience.
- **Memoized Performance**: Optimized to prevent unnecessary re-renders during state updates.

---

## 🛠️ Tech Stack

- **React**: Functional components and Hooks.
- **Context API**: Used for global state management (PostContext) to avoid prop drilling.
- **useEffect**: Leveraged for initial data loading and synchronizing the document title with the post count.
- **Faker.js (Optional)**: Often used in this project to generate the initial 30 atomic posts.

---

## 📂 Project Structure

```text
src/
├── PostContext.js    # The "Single Source of Truth" using Context API
├── Test.js           # Components used for performance testing
├── App.js            # Main entry point and component composition
└── index.css         # Custom styling for the Atomic UI
```

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/lexopez/atomic-blog_reactjs.git
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run the development server

```bash
npm start
```

Open your browser at:

```
http://localhost:3000
```

---
