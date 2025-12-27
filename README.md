# My Portfolio

## Project Overview
My Portfolio is a fast, responsive movie discovery app that showcases popular titles with powerful search and filtering. It uses the Kinopoisk API to fetch movie data, then presents it in a clean UI with dedicated detail pages for each title.

## Features
- **Search:** Find movies instantly by title.
- **Filters:** Narrow results by year, rating, and other criteria.
- **Detail Page:** View full movie information, including poster, description, rating, and metadata.

## Tech Stack
- **Vite** for fast builds and development.
- **React** for UI components.
- **JavaScript/TypeScript** (depending on project files) for application logic.
- **CSS** for styling.
- **Kinopoisk API** for movie data.

## Page Structure
- **Home/Search Page:** Search bar, filter controls, and movie grid/list.
- **Movie Detail Page:** Expanded info for a selected title, including summary, rating, and metadata.
- **Layout Components:** Shared header/footer and navigation.

## Setup Instructions
1. Install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env` file in the project root and add your Kinopoisk API key (see below).
3. Start the development server:
   ```bash
   npm run dev
   ```

## Configure Kinopoisk API Key
Create a `.env` file in the project root with the following entry:
```
VITE_KINOPOISK_API_KEY=your_api_key_here
```
Vite exposes variables prefixed with `VITE_` to the client. Replace `your_api_key_here` with your key from Kinopoisk.

## Running and Building
- **Run locally:**
  ```bash
  npm run dev
  ```
- **Build for production:**
  ```bash
  npm run build
  ```
- **Preview the production build:**
  ```bash
  npm run preview
  ```
