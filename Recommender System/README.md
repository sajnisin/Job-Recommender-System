# Content-based Job Recommender System with PySpark, SQL, TF-IDF & Cosine Similarity

## Description of Files

- `Job_Recommender_Spark_Codes.ipynb`: Notebook used to build & run the job recommender system, including data pre-processing, item profile creation (job listings), user profile creation (job seeker test cases), TF-IDF & matching by cosine similarity
- `Job_Recommender_Spark_Codes.py`: Exported from the above jupyter notebook
- `stopwords.txt`: Stopwords that are filtered out
- `test_cases.csv`: Inputs from job seekers (that will form the user profile)
- `output_job_skills_match.csv`: Output of the recommendation algorithm

## Code Execution:

The codes were executed in Google Colab as a Python Notebook (Job_Recommender_Spark_Codes.ipynb).

Key Environments:
- Python version 3.10.12
- OpenJDK version 11.0.22
- Pyspark version 3.5.1
- Scala version 2.12.18
- nltk version 3.8.1
- numpy version 1.25.2

The notebook was then exported to Job_Recommender_Spark_Codes.py

Command execution to run .py file:
!python Job_Recommender_Spark_Codes.py linkedin_job_posts_skills.csv stopwords.txt test_cases.csv output_job_skills_match.csv
