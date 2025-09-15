### Project Name & Slogan

**Project Name:** CineAI: AI-Powered Movie & Series Recommender
**Slogan:** Discover your next favorite film, powered by AI.

---

### Key Features

* **User Management:** Features include user registration, login with **JWT authentication**, and profile management.
* **Content Management:** Displays a comprehensive list of movies and series, along with detailed information pages.
* **AI-Powered Content Enhancement:**
    * **AI Summaries:** Uses the **Google Gemini API** to generate a concise summary for each film, helping users quickly grasp the plot.
    * **AI Tagging:** Employs the **Google Gemini API** to analyze a film's genre, synopsis, and cast to automatically generate relevant content tags (e.g., `#sci-fi`, `#philosophical`, `#cyberpunk`).
* **Smart Recommendations:**
    * **Tag-Based Recommendations:** Recommends films with similar AI-generated tags based on the user's viewing and liking history.
    * **Trending Content:** Showcases the most popular or highest-rated films across the platform.
* **Full-Text Search:** Integrates **Elasticsearch** to enable fast and precise searching by movie title, actor, director, or **AI tags**.
* **High-Performance Backend:** Built with **FastAPI** to handle requests asynchronously and utilizes **Redis** for caching popular data, significantly boosting performance.

---

### Technology Stack

* **Backend:** Python, FastAPI, SQLAlchemy
* **Database:** PostgreSQL
* **Full-Text Search:** Elasticsearch
* **Caching:** Redis
* **Artificial Intelligence:** Google Gemini API (Content Generation)
* **Frontend:** Vue.js or React
* **Deployment:** Docker, Docker Compose
