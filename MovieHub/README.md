# 🎬 MovieHub

MovieHub is a React-based movie browsing application that fetches data from [The Movie Database (TMDb)](https://www.themoviedb.org/) API.  
It allows you to explore movies, search by title, and save your favorites with a single click ❤️.

---

## 🚀 Features

- Browse **popular movies** from TMDb
- **Search movies** by title
- **Favorites page** to view saved movies
- **Favorite button** (🤍 → ❤️) to toggle favorites
- Responsive UI built with React + CSS

---

## 🛠️ Tech Stack

- **React** (Vite as build tool)
- **TMDb API** for movie data
- **CSS** for styling

---

## ⚙️ Setup Instructions

1. **Clone the repo**

   ```bash
   git clone https://github.com/AkshayAnithan/React-Series.git

   cd React-Series/MovieHub
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   - Copy .env.example to .env
   - Add your TMDb API key:

   ```bash
   VITE_API_KEY=your_tmdb_api_key_here
   ```

4. **Run the App**

   ```bash
   npm run dev
   ```

   Note: The app will start on http://localhost:5173/ (default Vite port).

---

## 🔑 Getting a TMDb API Key

1. Create an account at [TMDb](https://www.themoviedb.org/)

2. Go to your profile → Settings → API → Request an API Key.

3. Copy the key and paste it in your .env file.

---

### 📜 License

This project uses the TMDb API but is not endorsed or certified by TMDb.
Use it only for educational purposes.
