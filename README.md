# Food Identification and Nutrition Info

This project is a **calorie calculator** that identifies food items in images and provides detailed nutritional information about them. It uses a pre-trained Vision Transformer model to recognize food items and the API Ninjas Nutrition API to retrieve calorie and nutrition information.

![App Screenshot](data/data/sample.jpeg)

## Features
- **Identify food items** in an uploaded image.
- **Fetch nutrition information** (e.g., calories, fats, protein) based on the identified food.
- **Interactive UI** built using Gradio, allowing easy image uploads and viewing of nutrition details in a formatted HTML table.

## Technologies Used
- **Python** for backend processing
- **PIL** (Python Imaging Library) for image processing
- **Transformers** from Hugging Face for loading the Vision Transformer model
- **Gradio** for creating an interactive web-based UI
- **API Ninjas Nutrition API** for retrieving nutritional data

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sharad-18/Food-Identification-and-Nutrition-Info.git
   cd Food-Identification-and-Nutrition-Info
   pip install -r requirements.txt
   python app.py
