# 🎬 Netflix-Style Streaming SQL Project

This project is a mid-sized SQL database designed to simulate a streaming platform similar to Netflix. It showcases relational database design, complex SQL queries, use of foreign keys, data import from CSV, and trigger-based automation.

---

## 📁 Project Structure

- **SQL Schema**: Creation scripts for tables with relationships
- **Sample Data**: ~2,000 rows of generated data across multiple tables
- **Queries**: A wide range of SELECTs, JOINs, aggregations, and subqueries
- **Triggers**: Logic to automate certain behaviors (e.g. logging)


---

## 🗃️ Database Schema

The project includes the following interconnected tables:

- `users`: User profiles
- `subscriptions`: Plan details and subscription periods
- `movies`: Movie catalog with duration and release date
- `genres`: Genre master list
- `movie_genres`: Many-to-many between movies and genres
- `actors`: Actor profiles
- `movie_actors`: Many-to-many between movies and actors
- `watch_history`: Tracks what users watched and when
- `ratings`: User-submitted ratings
- `activity_log` (optional): Captures user activity via triggers

---

