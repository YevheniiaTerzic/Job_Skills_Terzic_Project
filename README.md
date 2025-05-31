# Overview

Welcome to my unique Python project, where I analyze the global job market to answer one key question:
"What should you do to land a high-paying data job in Europe?"

In this analysis, I explore data-related roles across the world, identifying the most in-demand positions, the key technologies you need to know, and the factors that influence salary levels. My goal is to provide data-driven insights for anyone aiming to grow their career in data — especially in the European market. 

# The Questions

1. Which data-related roles are the most popular in Europe and worldwide?
2. What technologies should you learn to land one of the top 3 in-demand roles?
3. How well are the most popular roles paid in Europe?
4. How can you maximize your salary as a Data Analyst? Which skills and other factors are most strongly correlated with higher pay?

# The Data
The main dataset sourced from [Luke Barousse's Python Course](https://lukebarousse.com/python) provides a foundation for my analysis, containing detailed information on job titles, salaries, locations, and essential skills. 

Additionaly I have used dictionary of European Union countries in csv format to separate EU region job postings for my analysis. 

I have also used API to load USD-EUR exchange rate from [Currency Exchange API]('https://open.er-api.com/v6/latest/USD') for calculating salaries in EUR.

# Tools I Used

For my deep dive into the data analyst job market, I harnessed the power of several key tools:

- **Python:** The core language behind my analysis — versatile and efficient for data manipulation and exploration. I worked with several key libraries:
    - **Pandas Library:** For reading, cleaning, and analyzing structured datasets.
    - **Matplotlib Library:** To create basic charts and visualize trends in the data.
    - **Seaborn Library:** For crafting more detailed and aesthetically pleasing visualizations.
- **Jupyter Notebooks:** My main workspace for combining code, visualizations, and commentary in one place, allowing for a clean and interactive workflow.
- **Visual Studio Code:** Used for editing and running Python scripts outside the notebook environment when needed.
- **Git & GitHub:** EUsed for version control and project sharing — helping track progress, collaborate, and store my code securely.
- **AI:** to generate a structured dictionary of EU countries, which was helpful in filtering and analyzing region-specific data.
- **[Currency Exchange API]('https://open.er-api.com/v6/latest/USD')** This API provides up-to-date exchange rates in JSON format. I used it to convert salaries from USD to EUR, ensuring the analysis is relevant and accurate for a European audience.

# Data Preparation and Cleanup