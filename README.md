week2-task-Akash-Verma

Student Performance Data Analysis (Week 2)

Files
- `student_performance_sample.csv` — sample dataset (20 rows)
- `student_performance_with_results.csv` — dataset with Pass/Fail column (generated)
- `week2-task-Akash-Verma.ipynb` — Jupyter notebook with all code & menu
- `README.md` — this file

How I approached the task
1. Created a reproducible sample dataset with 20 students and 4-5 columns: Name, Gender, Math, Science, English, StudyHours.
2. Built a Jupyter notebook that:
   - Loads the CSV using Pandas.
   - Displays first 5 rows and dataset information.
   - Calculates summary statistics (mean, median, max, min).
   - Uses NumPy for overall average and std deviation calculations.
   - Provides a function to search students by name (case-insensitive partial match).
   - Finds top 3 students by average.
   - Adds a Pass/Fail column using a threshold (>= 40).
   - Includes a small console menu for interactive exploration.

Steps to run
1. Download the files and place them in the same folder.
2. Open `week2-task-Akash-Verma.ipynb` in Jupyter.
3. Run cells from top to bottom.
4. To use the console menu, uncomment the `menu(df)` call in the designated cell and run it.

Challenges faced
- None significant; all operations are straightforward Pandas / NumPy usage. If you run into environment issues, ensure Pandas and NumPy are installed:
```
pip install pandas numpy
```

## Sample outputs
- The notebook prints the first five rows, dataset info, summary statistics, top 3 students, and saves an updated CSV with Pass/Fail results.(The outputs are provided within the code)
  
