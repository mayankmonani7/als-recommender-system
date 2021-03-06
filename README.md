# ALS-RECOMMENDER SYSTEM

Follow the instructions to get recommendations

1) Clone this repository
2) Download and Setup Apache PySpark
3) Open Anaconda Prompt
4) Go to the directory
5) eg. to get recommendation for "Iron Man" use this code -->> spark-submit --master local[4] --driver-memory 4g --executor-memory 8g als_recommender.py --movie_name "Iron Man" --top_n 10
