# DishCovery Recipe Chatbot 🍳

## 📖 Overview

DishCovery is a recipe recommendation system that helps users find the perfect dish based on their mood, available ingredients, or even a specific dish name. The idea is simple: just tell DishCovery what you're feeling or what you have on hand, and it will suggest dish names, necessary ingredients, and step-by-step recipes for how to make them.

Whether you're in the mood for something comforting or want to experiment with what's in your pantry, DishCovery makes it easy to whip up a delicious meal tailored to your tastes. By using the K-Nearest Neighbors (KNN) machine learning algorithm, it delivers suggestions that enhance your cooking experience. Plus, with an intuitive interface, navigating through your culinary options is a breeze.

## ✨ Features

- **Interactive Recipe Search**: Chatbot interface for searching recipes based on ingredients, mood, or dish names
- **User Authentication**: Sign-up and login functionality to personalize the user experience
- **Dynamic Content**: Interactive web pages with rich media content, including images and animations
- **Contact and About Pages**: Informative pages about the application and ways to contact the developers

## 🚀 Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Django
- **Database**: SQLite (default with Django)
- **Data Handling**: Pandas
- **Machine Learning**: scikit-learn (K-Nearest Neighbors)
- **Deployment**: Django Development Server (Localhost)
- **Version Control**: GitHub

## 🔧 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/VanshikaPanjwani/DishCovery-Recipe-Chatbot.git
   cd DishCovery
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Apply Migrations**:
   ```bash
   python manage.py migrate
   ```

4. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

5. **Access the Application**: 
   Open your web browser and navigate to `http://127.0.0.1:8000`

## 📁 Project Structure

```
DishCovery/
├── manage.py             # Django's command-line utility for administrative tasks
├── recipe/               # Django app with models, views, and templates
│   ├── admin.py          # Admin interface configurations
│   ├── apps.py           # Application configuration
│   ├── models.py         # Database models
│   ├── views.py          # Request handlers
│   ├── urls.py           # URL routing
│   ├── data/             # Directory containing project data files
│   │   └── food_data.csv # Contains data for recipes
│   └── migrations/       # Database migration files
├── templates/            # HTML templates for rendering web pages
├── static/               # Static files (images, CSS, JavaScript)
├── userproject/          # Main project configuration
│   ├── settings.py       # Project settings
│   ├── urls.py           # Root URL configurations
│   ├── wsgi.py           # Deployment interface (WSGI)
│   └── asgi.py           # Deployment interface (ASGI)
└── requirements.txt      # Python dependencies
```

## 📊 Data

- `recipe/data/food_data.csv`: Contains recipe data that powers the recommendation system

## 💬 Usage

### Features and Functionality

1. **Mood-Based Recipe Suggestions**: 
   - The chatbot suggests recipes based on your mood
   - Provides the recipe name, steps, and ingredients needed

2. **Dish Name-Based Recipe Search**: 
   - Input a dish name to get the relevant recipe details
   - Includes recipe steps and ingredients required

3. **Ingredient-Based Recipe Search**: 
   - Enter a list of ingredients to get recipe suggestions
   - Shows recipe name, steps, and ingredients needed

## 🧠 How It Works

DishCovery uses the K-Nearest Neighbors (KNN) machine learning algorithm to match user inputs with the most suitable recipes. The system:

1. Processes user input (mood, ingredients, or dish name)
2. Uses KNN to find similar recipes in the dataset
3. Returns personalized recipe suggestions
4. Provides complete cooking instructions and ingredient lists

## 🛠️ Development

To contribute to the development:

1. Fork the repository
2. Create a feature branch
3. Implement your changes
4. Submit a pull request

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📞 Contact

For more information, you can contact the project maintainer at:

- **GitHub**: [https://github.com/VanshikaPanjwani](https://github.com/VanshikaPanjwani)

---

<p align="center">Made with ❤️ for food lovers everywhere</p>
