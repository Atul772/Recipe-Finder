# Recipe Generator

## Recipe Searching with Python

This project is a Python-based website that uses Flask for backend logic. It allows users to search for recipes based on ingredients or preferences.
I have done this project with my friend Raviranjan (@kumarranjan78084), as our project for python course.


## Features
- **Recipe Recommendation**: Generate recipes based on input preferences like cuisine type, dietary restrictions, and available ingredients.
- **Large Dataset**: Utilizes a dataset containing 6000 recipes with details like ingredients, preparation time, and cuisine type.
- **Customizable**: Users can specify dietary preferences (e.g., vegetarian, gluten-free) and ingredient availability.

## Requirements
- Python 3.x
- pandas
- Flask (for web API and rendering templates)

## Setup Instructions

1. **Clone the Repository**:
   
    git clone https://github.com/Atul772/Recipe-Finder.git

2. **Install Dependencies**:
    Use `pip` to install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. **Dataset**:
    - The dataset used for training the model is available in `data/recipes.csv`. Ensure that the dataset is in the correct format and the required columns (e.g., ingredients, cuisine, recipe name) are present.

4. **Run the Web App**:
    - The app is built using Flask. To run the web server, execute:
    ```bash
    python app.py
    ```
    Visit `http://localhost:5000` in your browser to interact with the Recipe Generator.

## Usage
- **Web Interface**: Users can input preferences such as available ingredients or dietary restrictions via the web interface, and the app will generate a list of recipe recommendations.
- **Command-Line Interface (CLI)**: You can also interact with the model via a Python script to generate recipes programmatically.
