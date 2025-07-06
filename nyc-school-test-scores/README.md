# Exploring NYC Public School Test Scores

This project analyzes SAT performance across New York City's public high schools. The SAT includes three sections—Math, Reading, and Writing—each scored out of 800. The goal is to uncover insights that inform educators, policymakers, and families.

## Objective

- Identify schools with top math performance.
- Rank the top 10 schools based on total SAT scores.
- Compare borough-level SAT performance and variability.

## Project Instructions

1. **Best Math Results**  
   - Define the best math result as 80% or more of the max score (800).  
   - Save results as a DataFrame `best_math_schools` with columns: `school_name`, `average_math`, sorted in descending order.

2. **Top 10 Schools by Total SAT**  
   - Create a new column `total_SAT` as the sum of math, reading, and writing scores.  
   - Save the top 10 schools in a DataFrame `top_10_schools` with `school_name` and `total_SAT`, sorted in descending order.

3. **Borough with Highest Score Variation**  
   - Group by `borough` and calculate count, mean, and standard deviation of `total_SAT`.  
   - Save the borough with the highest standard deviation as a one-row DataFrame `largest_std_dev` with columns:  
     `borough`, `num_schools`, `average_SAT`, `std_SAT` (rounded to 2 decimal places).

## Key Findings

- **Stuyvesant High School** had the highest math (754) and total SAT score (2144).
- Other top math schools scored above 680, including Bronx Science, Staten Island Tech, and Queens High School for the Sciences.
- The **top 10 schools** by total SAT scored between **1889 and 2144**.
- **Manhattan** showed the highest variation in scores, with a standard deviation of **230.29** across **89 schools**.

