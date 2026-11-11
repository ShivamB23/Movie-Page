# 🎬 Movie App

A responsive movie browsing and search app built with React. It pulls live data from [The Movie Database (TMDB) API](https://www.themoviedb.org/) so users can discover popular movies, search by title, and navigate between pages.

## ✨ Features

- Browse popular movies on the home page
- Search for movies by title
- Reusable `MovieCard` component with conditional rendering
- Multi-page navigation with client-side routing
- Global state management with the React Context API
- Asynchronous data fetching with `useEffect`
- Responsive UI styled with custom CSS

## 🛠 Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [React Router](https://reactrouter.com/)
- [TMDB API](https://developer.themoviedb.org/docs)
- CSS

## 📁 Project Structure

```
src/
├── components/     # Reusable UI components (MovieCard, NavBar)
├── contexts/       # React Context providers
├── css/            # Stylesheets
├── pages/          # Page components (Home, Favorites)
├── services/       # API calls (api.js)
├── App.jsx
└── main.jsx
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/download) (v18 or later recommended)
- A free TMDB API key ([get one here](https://www.themoviedb.org/settings/api))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Add your API key**

   Create a `.env` file in the project root:
   ```env
   VITE_TMDB_API_KEY=your_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. Open the URL printed in your terminal (usually `http://localhost:5173`).

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## 🔮 Future Improvements

- Movie detail pages
- Pagination or infinite scroll
- Genre filters and sorting
- Persisting favorites in `localStorage`
- Unit tests with Vitest and React Testing Library

## 👤 Author

**Shivam Bhat**
- GitHub: [ShivamB23](https://github.com/ShivamB23)
- LinkedIn: [Shivam Bhat](https://www.linkedin.com/in/shivam-bhat-942343312/)

## 🙏 Acknowledgements

This product uses the TMDB API but is not endorsed or certified by [TMDB](https://www.themoviedb.org/).

