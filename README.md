# 🎬 CINEVERSE — Your Universe of Cinema

An AI-powered movie discovery and community platform for cinema enthusiasts.

🌐 **Live Demo:** https://cineverse-usrj.hatchable.site

## ✨ Features

- **Movie Discovery:** Explore trending, popular, top-rated, upcoming movies, and hidden gems.
- **CineAI:** Get conversational movie recommendations powered by Google Gemini and verified TMDB movie data.
- **Movie Explorer:** Explore movie descriptions, cast, crew, ratings, and details.
- **My Cinema:** Maintain personal watchlists, watched movies, favourites, and collections.
- **Reviews & Ratings:** Write, edit, delete, and like movie reviews.
- **Cinema Statistics:** Track watched movies, ratings, favourite genres, and directors.
- **CineQuiz:** Test movie knowledge through mixed, scene-clue, release-year, and plot-clue quizzes.
- **CineCommunity:** Discover cinephiles, follow profiles, and explore community reviews.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | JavaScript API functions |
| Database | PostgreSQL |
| Authentication | Hatchable Authentication |
| AI Integration | Google Gemini |
| Movie Database | TMDB API |
| Hosting | Hatchable |

## 🏗️ Project Structure

```text
CINEVERSE/
├── public/
│   ├── index.html
│   ├── login.html
│   ├── app.js
│   └── theme.css
├── api/
│   ├── cineai.js
│   ├── community.js
│   ├── library.js
│   ├── collections.js
│   ├── reviews.js
│   ├── quiz.js
│   ├── stats.js
│   └── movies/
├── lib/
│   └── tmdb.js
├── migrations/
├── hatchable.toml
└── README.md
```

## 🤖 How CineAI Works

1. The user describes a movie preference, genre, or mood.
2. The backend retrieves candidate movies from TMDB.
3. Google Gemini analyses the verified candidates.
4. Recommendations are matched against actual TMDB movie IDs.
5. The platform displays movie recommendations with explanations.

This approach helps prevent fictional or unverified movie recommendations.

## 🔐 Security

- API keys are stored as server-side secrets.
- User-specific library and collection data is protected through database access policies.
- Review and community operations enforce ownership.
- Authentication protects personal account features.

## 🚀 Live Demo

Visit **https://cineverse-usrj.hatchable.site** and create an account to explore personalized features.

## 📸 Screenshots

Screenshots of the homepage, movie discovery, CineAI, library, and community will be added here.

## 🎯 Project Objective

CINEVERSE was developed as a hands-on full-stack development project to explore frontend development, backend APIs, database design, authentication, third-party API integration, and AI-powered applications.

**Built for the love of cinema.** 🍿
