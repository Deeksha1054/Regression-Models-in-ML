#  Types of Regression in Machine Learning

This project demonstrates **eight major types of regression algorithms** used in machine learning. Each section includes a concise explanation, synthetic data generation, model training, prediction, and visualization using Python and popular libraries like `scikit-learn` and `matplotlib`.

---

##  Table of Contents

* [Overview](#overview)
* [Types of Regression](#types-of-regression)

  * [1. Linear Regression](#1-linear-regression)
  * [2. Polynomial Regression](#2-polynomial-regression)
  * [3. Stepwise Regression](#3-stepwise-regression)
  * [4. Decision Tree Regression](#4-decision-tree-regression)
  * [5. Random Forest Regression](#5-random-forest-regression)
  * [6. Support Vector Regression (SVR)](#6-support-vector-regression-svr)
  * [7. Ridge Regression](#7-ridge-regression)
  * [8. ElasticNet Regression](#8-elasticnet-regression)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

---

##  Overview

Regression analysis is a key statistical technique in machine learning used to model the relationship between a dependent variable and one or more independent variables. This project illustrates:

* Model training on synthetic non-linear data (`y = sin(x) + noise`)
* Visualization of how different regression techniques fit the same dataset
* Insights into model strengths and weaknesses

---

##  Types of Regression

### 1. Linear Regression

Fits a straight line to model the linear relationship between input and output.

### 2. Polynomial Regression

Adds polynomial features to model non-linear relationships.

### 3. Stepwise Regression

Selects the most significant features using statistical tests (`SelectKBest`).

### 4. Decision Tree Regression

Splits the data into regions with decision rules and predicts region-wise averages.

### 5. Random Forest Regression

Ensemble of decision trees to reduce overfitting and improve accuracy.

### 6. Support Vector Regression (SVR)

Uses the support vector machine framework with an epsilon-insensitive tube.

### 7. Ridge Regression

Linear regression with L2 regularization to reduce coefficient variance.

### 8. ElasticNet Regression

Combines L1 (Lasso) and L2 (Ridge) regularization for a balanced model.

---

##  Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/regression-algorithms.git
cd regression-algorithms
```

2. Install dependencies:

```bash
pip install numpy matplotlib scikit-learn
```

---

##  Usage

Run the Python file or open the notebook:

```bash
python regression_examples.py
```

Or open in Jupyter Notebook:

```bash
jupyter notebook
```

Each section will:

* Generate synthetic data
* Train the respective regression model
* Plot the results

---


# The Smartest AI Nutrition Assistant

**A multimodal generative AI system that understands food images, user queries, and nutrition goals to deliver personalized meal recommendations and nutritional insights.**

---

##  Project Overview

In today's health-conscious world, individuals are increasingly looking for *personalized*, *context-aware*, and *intelligent* nutrition guidance. However, most tools fall short—they’re generic, inflexible, and ignore personal needs like allergies, culture, or health goals.

---

##  Key Components

| Module                 | Description                                                     |
| ---------------------- | --------------------------------------------------------------- |
| `BLIP`                 | Detects food items from images using image captioning           |
| `GPT-2` (Hugging Face) | Responds to user queries using text generation                  |
| `food.csv` (dataset)   | Contains detailed nutritional info used for calorie lookup      |
| `matplotlib/seaborn`   | For visualizing calorie/protein/fat/carbs distribution in meals |

---

##  Features Implemented

*  Image-Based Food Recognition:**
  Captures an image URL and uses BLIP to identify food items visually.

*  Text-Based Nutrition Q\&A:**
  Ask questions like *"Why is spinach healthy?"* or *"Is peanut butter good for muscle gain?"*

*  Personalized Meal Plan Generator:**
  Based on user goals (e.g., weight loss) and allergies, generates a basic sample meal plan.

*  Meal Nutrition Visualizer:**
  Displays bar chart of calories, carbs, fats, and proteins for selected meals.

---

## 🖼 Sample Run

```python
img_url = "https://example.com/steak-image.jpg"
caption = caption_image(img_url)
print("Detected Food:", caption)

food, calories = estimate_calories_with_assumption(caption)
print(f"Estimated calories for one portion of {food}: {calories:.2f} kcal")
```

---

##  How to Use

1. Upload your food nutrition dataset (like `food.csv`)
2. Run the notebook to load the models and data
3. Use:

   * `caption_image(image_url)` to detect food
   * `ask_bot(query)` to ask health or diet questions
   * `generate_meal_plan(goal, allergies, preferences)` to get a diet plan
   * `visualize_nutrition(meal_plan)` to see nutrition stats

---

##  Future Work

* Train a deep learning model for **real image-based calorie estimation** using portion detection
* Add **voice input** or **chat interface**
* Integrate **wearable health data** (e.g., Fitbit/Apple Health) for smarter recommendations
* Use **LLMs like GPT-4 + LangChain** for contextual dialogue and feedback adaptation

---

## Data Source

* [USDA Food Nutrition Dataset](https://fdc.nal.usda.gov/download-datasets.html)
* HuggingFace BLIP & GPT-2 models

---

## Tech Stack

* Python 🐍
* PyTorch / Transformers 🤗
* BLIP (Salesforce) 📸
* GPT-2 🧠
* pandas, seaborn, matplotlib 📊

## ACKNOWLEDGEMENT 
Dr. Agughasi Victor I.

