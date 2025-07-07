````markdown
# NU_CIS-2025-20_Assessment

Solution for the Nile University CIS 48-Hour Challenge.

## Files

- **Tasks_Code.ipynb** – Notebook for Part 1 (graph + simulation) and Part 2 (Q-learning advisor)
- **courses_data.csv** – Master course list (ID, name, credits, tag, prerequisites)
- **students.csv** – Generated student records
- **trained_model.pkl** – Saved Q-table
- **courses_Graph.html** – Interactive curriculum graph
- **student_\<ID\>_graph.html** – Per-student graphs

## Usage

1. Open **Tasks_Code.ipynb** in Colab.
2. Change the path to your CSV at the top:
   ```python
   courses_File = "courses_data.csv"
````

3. Run all cells.
4. toogle to the table of contents to navigate better, you can View `courses_Graph.html` or go to results section in Task 1 part to call the in-notebook visual for student courses progress, or results section in Task 2 to test the recomendation suggestion for a semester for a student.
