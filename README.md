# Meal Muse

Meal Muse is a comprehensive recipe recommendation platform designed to revolutionize meal planning. By leveraging data-driven techniques and the MERN stack (MongoDB, Express, React, Node.js), Meal Muse provides users with tailored meal suggestions based on their unique preferences, dietary needs, and available ingredients. This project aims to simplify meal planning, promote healthier eating habits, and empower individuals to make informed dietary decisions.

## Features

- **Personalized Recipe Recommendations**: Tailored meal suggestions based on time, calories, ingredients, and nutritional goals.
- **Dynamic Recipe Filters**:
  - Time-based meal preparation options.
  - Calorie-based recipes for mindful eating.
  - Ingredient-based suggestions for resource efficiency.
  - Nutrition-based recommendations for health-conscious choices.
- **Detailed Recipe Page**:
  - Key details: preparation time, servings, calories.
  - Step-by-step cooking instructions.
  - Nutritional breakdown.
  - Options to save favorites, share, and print.
- **Interactive Dashboard**: Manage profile, view favorites, and personalize preferences.
- **Advanced Search and Explore**: Effortlessly find recipes by name or category with pagination for smooth navigation.
- **User Authentication**: Secure account creation and login.
- **Quiz Feature**: Personalized recommendations based on user responses to dietary and health-related questions.

## Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## Installation

Follow these steps to set up Meal Muse locally:

### Prerequisites

1. Ensure **Node.js** and **npm** are installed.
2. Install **MongoDB** and ensure it is running.

### Frontend Setup

1. Clone the frontend repository:
   ```bash
   git clone https://github.com/your-username/meal-muse-frontend.git
   cd meal-muse-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### Backend Setup

1. Clone the backend repository:
   ```bash
   git clone https://github.com/your-username/meal-muse-backend.git
   cd meal-muse-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root directory with the following variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Connecting Frontend and Backend

1. Ensure the frontend is running at `http://localhost:3000`.
2. Ensure the backend is running at `http://localhost:5000`.
3. Update the API base URL in the frontend code to match the backend server’s URL.

### Testing

1. Open your browser and navigate to `http://localhost:3000` to access the Meal Muse platform.
2. Register or log in to explore the personalized features.

## Project Structure

### Frontend
```
meal-muse-frontend/
|-- src/
|   |-- components/
|   |-- pages/
|   |-- services/
|-- public/
|-- package.json
```

### Backend
```
meal-muse-backend/
|-- models/
|-- routes/
|-- controllers/
|-- middlewares/
|-- config/
|-- package.json
```

## Screenshots

### Landing Page
![Landing Page](https://via.placeholder.com/800x400 "Hero Section")

### Recipe Details
![Recipe Details](https://via.placeholder.com/800x400 "Recipe Details")

### Dashboard
![Dashboard](https://via.placeholder.com/800x400 "Dashboard")

## Contribution Guidelines

We welcome contributions to enhance Meal Muse. To contribute:

1. Fork the repository.
2. Create a new branch for your feature/fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For inquiries or support, contact:

- **Sai Harika**
- Email: [your-email@example.com](mailto:your-email@example.com)
- GitHub: [https://github.com/your-username](https://github.com/your-username)

---

Meal Muse is a labor of love, combining technology and culinary art to simplify meal planning. Explore, experiment, and enjoy a healthier lifestyle with Meal Muse!