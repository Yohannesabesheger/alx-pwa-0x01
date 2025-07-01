# 🎬 CineSeek

CineSeek is a modern movie discovery application built with **Next.js**, **TypeScript**, and **Tailwind CSS**. It allows users to explore movies from the **MoviesDatabase API**, search by year or genre, and view detailed information on each film.

The goal of CineSeek is to demonstrate clean architecture, responsive UI design, reusable components, and effective API integration using current web development best practices.

---

## 🚀 Project Features

- 🎥 Browse movies from a public API
- 🔍 Filter by year or genre
- 📄 View detailed movie information
- ⚙️ Type-safe API integration with TypeScript
- 🧱 Reusable, modular React components
- 🎨 Responsive design using Tailwind CSS
- ⚠️ Proper error handling and loading states
- 🔐 Secure API key handling with `.env.local`

---

## 🎯 Learning Objectives

- Understand and use API documentation
- Integrate third-party APIs with Next.js
- Create and use TypeScript interfaces for API responses
- Build responsive UIs with Tailwind CSS
- Manage state for filtering and pagination
- Handle loading and error states gracefully
- Use Next.js API routes for server-side data fetching
- Manage environment variables securely

---

## 🧰 Tech Stack

| Category  | Stack                                                              |
| --------- | ------------------------------------------------------------------ |
| Framework | [Next.js 14 (Pages Router)](https://nextjs.org)                    |
| Language  | TypeScript                                                         |
| Styling   | Tailwind CSS                                                       |
| Icons     | Font Awesome                                                       |
| API       | [MoviesDatabase API](https://www.themoviedb.org/documentation/api) |

---

## 📦 Requirements

- Node.js v16 or higher
- npm or yarn
- Git

---

## 📁 File Structure

```
alx-movie-app/
├── components/
│   ├── commons/
│   │   ├── Button.tsx
│   │   ├── Loading.tsx
│   │   └── MovieCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── fetch-movies.ts
│   ├── movies/
│   │   └── index.tsx
│   ├── _app.tsx
│   └── index.tsx
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .eslintrc.json
├── .gitignore
├── next.config.js
├── package.json
└── tsconfig.json
```

---

## 🛠 Setup & Run

1. Clone the repo:

   ```bash
   git clone https://github.com/YOUR_USERNAME/alx-movie-app.git
   cd alx-movie-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create your `.env.local` file and add your MoviesDatabase API key:

   ```env
   MOVIES_API_KEY=your_api_key_here
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Visit [http://localhost:3000](http://localhost:3000)

---

## 🧪 Future Improvements

- Add user authentication
- Support for bookmarking favorite movies
- Dark mode toggle
- Pagination for infinite scroll

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---
