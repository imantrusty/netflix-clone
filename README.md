# **Netflix Clone**

A fully responsive Netflix clone application built using **React.js**, **JavaScript**, **CSS**, and **Firebase**, with movie data dynamically fetched from **The Movie Database (TMDB) API**. This project replicates the core functionalities and features of a modern streaming platform.

---

## **Features**

- **Dynamic Movie Rows**: Movie data fetched via the TMDB API and displayed in categorized rows.
- **Interactive Banner**: Featured content displayed with engaging visuals.
- **Trailer Playback**: Trailer videos play when users click on a movie, enhancing interactivity.
- **Responsive Navbar**: A sleek and functional navigation bar styled with CSS.
- **Firebase Integration**: Backend configured for secure hosting and efficient deployment.

---

## **Technologies Used**

- **Frontend**: React.js, JavaScript, CSS
- **Backend**: Firebase
- **API**: TMDB (The Movie Database)

---

## **Development Process**

1. **Set Up the Project Environment**
   - Initialized a React application using **VS Code** and install necessary extensions.
   - Configured **Firebase** for backend functionality.

2. **API Integration**
   - Obtained TMDB API Key and fetched movie data dynamically.
   - Designed a structure to display movies in rows by category.

3. **UI/UX Enhancements**
   - Developed a responsive **banner** for featured content.
   - Built a **Navbar** with CSS for intuitive navigation.

4. **Interactive Features**
   - Added functionality to display trailer videos using **JavaScript**.
   - Enhanced responsiveness for optimal viewing across devices.

5. **Deployment**
   - Hosted the application on Firebase for easy access and sharing.

---

## **Getting Started**

### **Prerequisites**
- Node.js installed on your system.
- A TMDB API key (sign up for free [here](https://www.themoviedb.org/)).

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/netflix-clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd netflix-clone
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### **Run Locally**
1. Create a `.env` file in the root directory and add your TMDB API key:
   ```env
   REACT_APP_TMDB_API_KEY=your_api_key_here
   ```
2. Start the development server:
   ```bash
   npm start
   ```

The application will be accessible at `http://localhost:3000`.

---

## **Project Structure**

```
netflix-clone/
├── public/
├── src/
│   ├── components/
│   │   ├── Banner.js
│   │   ├── MovieRow.js
│   │   └── Navbar.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── .env
├── package.json
└── README.md
```

---

## **Future Enhancements**

- Add user authentication for personalized experiences.
- Include search functionality for finding specific movies or shows.
- Integrate a "My List" feature to allow users to save favorites.

---

## **Live Demo**

Check out the live application here: [[Live Demo]](https://netflix-clone-5d4cf.web.app/)
