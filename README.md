# MenuRoulette

A Python-based automation project applying data handling and randomization logic to streamline weekly meal planning. Demonstrates practical use of data structures and workflow optimization through code.

## Overview

The project is organized into two notebooks:
- Menu.ipynb – Contains categorized recipe dictionaries for easy, intensive, pasta, and fish meals, plus a lunch list. This structure makes it simple to add, remove, or edit recipes.
- MenuRoulette.ipynb – Randomly selects meals from each category (without repetition) to create a balanced weekly plan.

Meal Planning Logic

The script generates one week of meals with the following structure:
- 1 pasta day
- 1 fish day
- 2 leftover days
- 1 intensive meal
- 2 quick meals

This setup ensures variety and practicality — no making a two-hour lasagna on a busy weeknight or eating pasta five days in a row! Lunches repeat for the week to simplify prep.


## How to Run

Clone the repository:
git clone https://github.com/<your-username>/MenuRoulette.git
cd MenuRoulette


Open the notebooks in Jupyter or VS Code with Jupyter support.
Run Menu.ipynb first to load or edit your recipe dictionaries.
Run MenuRoulette.ipynb to generate your weekly meal plan and shopping list.

Requirements:
Python 3.x
Jupyter Notebook
Standard Python libraries (random, pandas, etc.)

## Future Improvements

1. Export shopping lists to CSV or PDF
2. Add support for dietary preferences or restrictions
3. Include a GUI or web app interface for easier interaction
4. Automatically track ingredient frequency or cost
5. Integrate with grocery APIs for online ordering

### Author
Created by Jennifer Conte — developed to make meal planning faster, easier, and more fun.
