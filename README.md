# Netflix-Data-Cleaning-Exploratory-Data-Analysis.
This project focuses on cleaning and analyzing the Netflix Prize dataset containing over 23 million ratings.  The objective was to transform raw hierarchical text data into a structured dataset and perform professional exploratory data analysis (EDA) to extract meaningful insights.


##Project Files

#1. clean_data_file1.ipynb

- Loaded raw hierarchical rating dataset

- Extracted MovieID from header rows

- Forward-filled MovieID values

- Structured ratings into proper columns

 #2. clean_moviesname_file2.ipynb

- Loaded movie metadata file

- Handled encoding issues

- Cleaned Year and Title columns

- Removed inconsistencies

#3. clean_rating_file.3ipynb.ipynb

- Removed null values

- Validated rating range (1–5)

- Optimized memory usage

- Converted datatypes for efficiency

#4. merge_files_and_analysis_file4.ipynb

- Merged ratings and movie metadata

- Removed unmatched records

- Performed structured EDA

- Created visualizations using Matplotlib & Seaborn

- Extracted statistical insights


##Dataset Information

-> 23.8 Million Ratings

-> 470K+ Unique Users

-> 4,493 Movies

-> 6 Structured Columns



##Key Insights

-> Ratings are concentrated around 3–4, indicating positive user bias.

-> User activity follows a heavy-tailed distribution (few highly active users).

-> A small fraction of movies dominate total engagement.

-> Popularity and average rating show weak correlation.

-> Platform activity increased significantly over time.



##Tools & Technologies

-> Python

-> Pandas

-> NumPy

-> Matplotlib

-> Seaborn

If you find this project interesting, feel free to explore the notebooks and share feedback :)
