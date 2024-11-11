# Forkify 🍴

Forkify is a JavaScript-based web application that allows users to search for recipes, view detailed instructions and manage a personal list of bookmarked recipes. Built with vanilla JavaScript and deployed on Netlify, this project demonstrates core front-end development concepts such as API integration, modular JavaScript, asynchronous programming and DOM manipulation.

## Deployed Version

You can access the deployed version of the app here: [Forkify App](https://forkify-recipes-js.netlify.app/)

## Features

- **Recipe Search**: Fetches recipes from the Forkify API based on user input.
- **Recipe Details**: Displays ingredients, preparation time, servings and cooking instructions.
- **Bookmark Recipes**: Allows users to save and manage a list of favorite recipes.
- **Adjust Servings**: Dynamically update ingredient quantities based on the desired number of servings.
- **Responsive UI**: Designed to work on both desktop and mobile devices.

## Technologies Used

- **HTML5 & CSS3**: Basic structure and styling of the application.
- **JavaScript (ES6+)**: Core logic, asynchronous programming with `async/await` and ES6+ modules.
- **Forkify API**: Provides recipe data for search functionality.
- **Parcel**: Bundler for development and production builds.
- **Netlify**: Used for deploying the application with continuous integration.

## Project Structure

The project is structured to keep components modular and organized, with separation between data handling, application logic and user interface components.

## Getting Started

### Prerequisites

To run the Forkify app locally, you need a modern web browser and Node.js installed for any additional development tasks.

- [Node.js](https://nodejs.org/)
- npm (Node Package Manager)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/filosoho/JavaScript-Projects.git
   ```

   ```bash
   cd JavaScript-Projects/Forkify
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the application locally:

   ```bash
   npm run start
   ```

   This will start a local development server with Parcel, allowing you to view the app at http://localhost:1234.

4. Build the application for production:

   ```bash
   npm run build
   ```

   The production-ready files will be outputted to the dist folder.

## API Configuration

The app fetches data from the Forkify API to retrieve recipe details. You can configure the API URL and request timeout in config.js if required.

## Usage

1. **Search for Recipes**: Enter a keyword (e.g., "pizza" or "chicken") in the search bar to fetch recipes.
2. **View Recipe Details**: Click on a recipe from the search results to see full details, including ingredients and preparation steps.
3. **Bookmark a Recipe**: Click the bookmark icon to save a recipe to your bookmarks list for easy access.
4. **Adjust Servings**: Use the servings adjuster to automatically update ingredient quantities based on your needs.

## Contributing

Contributions are welcome! To improve this project:

- Fork the repository.
- Create a new branch (feature/your-feature-name).
- Commit and push your changes.
- Submit a pull request with a description of your updates.

---

Forkify provides a streamlined recipe browsing and bookmarking experience with a focus on modular, maintainable JavaScript code. Enjoy exploring recipes and happy cooking!
