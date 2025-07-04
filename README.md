
# MoviesDatabase API Integration

This project integrates with the MoviesDatabase API to fetch and manage movie-related data such as titles, genres, ratings, and more.

---

## API Overview

The MoviesDatabase API provides a wide range of data about movies, TV shows, and related content. It includes endpoints to search, retrieve, and filter content, allowing developers to build powerful media-centric applications.

---

## Version

**v1**

---

## Available Endpoints

- `GET /titles`: Retrieves a list of movies or shows.
- `GET /titles/{id}`: Fetch detailed information for a specific title by ID.
- `GET /titles/search/title/{title}`: Search for movies or shows by title.
- `GET /titles/random`: Get a randomly selected movie or show.
- `GET /titles/utils/genres`: List all available genres.

---

## Request and Response Format

### Example Request (Search by Title)
```http
GET /titles/search/title/Inception
