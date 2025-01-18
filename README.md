# Real-Time Recommendation System

## Overview
This project implements a real-time recommendation system suitable for e-commerce platforms. The system uses two primary methods to suggest products to users:

1. **Content-Based Filtering**: Recommends products similar to a given product based on its attributes, such as description and category.
2. **Collaborative Filtering**: Suggests products by analyzing user interactions and finding similar users.

## Features
- **Content-Based Recommendations**: Utilizes the product description to find similar items using TF-IDF vectorization and cosine similarity.
- **Collaborative Filtering**: Leverages user-item interaction data to recommend products based on similar user preferences.
- Built with scalable and efficient algorithms to handle moderate-sized datasets.

## Prerequisites
To run this project, ensure you have the following installed:
- Python 3.8 or higher
- Required Python libraries:
  - `pandas`
  - `scikit-learn`
  - `scipy`

Install the required libraries using the following command:
```bash
pip install pandas scikit-learn scipy
```

## How to Run
1. Clone the repository or download the project files.
   ```bash
   git clone <repository-url>
   cd path/to/project
   ```
2. Run the Python script:
   ```bash
   python recommendation_system.py
   ```
3. View the output recommendations in the terminal.

## Input Data
The project uses sample datasets:
- **Product Catalog**: A list of products with attributes like name, category, and description.
- **User Interactions**: A dataset containing user IDs, product IDs, and ratings.

You can modify these datasets to test the system with your own data.

## Example Output
- Content-Based Recommendations for Product 1:
  - Headphones
  - Keyboard
  - Mouse

- Collaborative Filtering Recommendations for User 1:
  - Smartphone
  - Keyboard

## Customization
- Adjust the `top_n` parameter in the recommendation functions to change the number of recommendations.
- Replace the sample data with your own datasets for real-world testing.

## Limitations
- Content-based filtering depends heavily on the quality of product descriptions.
- Collaborative filtering requires sufficient user interaction data for accurate recommendations.


### Concise Description
A real-time recommendation system for e-commerce platforms that uses content-based and collaborative filtering techniques to provide personalized product suggestions.


