# Movie Database Project

A React-based web application that allows users to search for movies and view detailed information about them using The Movie Database (TMDb) API. This project demonstrates key React concepts like components, JSX, state management, and routing.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [Usage](#usage)
-

## Features
- Search for movies by title using the TMDb API.
- View a grid of movie cards with posters, titles, release dates, and short descriptions.
- Click a movie card to see detailed information (rating, full overview, etc.) on a separate page.
- Responsive design with loading and error states.
- Clean, modern styling with CSS.

## Technologies Used
- **React**: Frontend library for building the UI.
- **React Router**: For navigation between the home page and movie details.
- **Axios**: To fetch data from the TMDb API.
- **TMDb API**: Provides movie data (requires an API key).
- **CSS**: Custom styles for layout and design.
- **Node.js**: Runtime environment for development.

## Setup Instructions
Follow these steps to get the project running locally:

### Prerequisites
- Node.js (v14 or higher) installed. Download from [nodejs.org](https://nodejs.org).
- A TMDb API key. Sign up at [The Movie Database](https://www.themoviedb.org/) and get your key from the API section.

### Installation
1. **Clone the repository**:https://github.com/Stephan-23/movie-database.git
   cd movie-database
2. **Install dependencies**: npm install
3. **Configure the API key**:
- Open `src/api.js`.
- Replace `YOUR_API_KEY` with your TMDb API key:
  ```jsx
  const API_KEY = 'your-tmdb-api-key-here';
  ```

4. **Start the development server**:   npm start


## Usage
- **Home Page**: Type a movie title (e.g., "Avengers") in the search bar and click "Search" to see a list of matching movies.
- **Movie Details**: Click any movie card to view its full details, including a larger poster, rating, and overview.
- **Navigation**: Use the "Back to Search" link or the header to return to the home page.







