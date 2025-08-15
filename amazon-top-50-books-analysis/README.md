Amazon Top 50 Bestselling Books (2009–2019): Data Analysis

Tools Used: Python, Pandas, Matplotlib, Jupyter Notebook

Goal: Analyze Amazon Top 50 books (2009–2019) to find most reviewed books, genre popularity, and Average ratings per genre.

Files

 "Amazon_Top50_Books_Analysis.ipynb" – full code & analysis
 
 "Amazon_Top50_Books_Analysis.pdf" – formatted report
 
 "bestsellers_with_categories.csv" – dataset
 
 "plots/" – exported charts

Steps Performed
 1. Imported dataset into Pandas DataFrame
 2. Sorted top 50 books by review count
 3. Removed duplicate titles
 4. Grouped by:
   - Book Title → summed reviews across years
   - Genre → calculated average ratings & total reviews
 5. Created visualizations:
   - Top 5 books by total reviews
   - Total reviews by genre

Key Findings
- Most Reviewed Book (2009–2019):
  Gone Girl – 171,813 reviews (across all years)
- Genre Popularity:  
  - Fiction: ~1.49M reviews  
  - Non Fiction: ~377K reviews
- Ratings: 
  - Non Fiction has a higher average rating (4.72) vs Fiction (4.49)
- Popularity doesn’t always equal higher rating (Gone Girl had only 4.0 rating).

How to Reproduce:
1. "pip install pandas matplotlib"
2. Open "Amazon_Top50_Books_Analysis.ipynb" in Jupyter
3. Run all cells

Next Steps
- Year-wise trend analysis
- Price vs Rating/Reviews relationship

- Add confidence intervals / statistical tests

