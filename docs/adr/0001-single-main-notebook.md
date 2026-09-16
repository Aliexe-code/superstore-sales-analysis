# Single Main Notebook as Source of Truth

Eman's repo had only `notebooks/01_questions_and_setup.ipynb`; supporting notebooks risk fragmenting the deliverable. We decided the repo will have one reproducible `Superstore_Analysis.ipynb` at the root as the graded deliverable, with `notebooks/02_cleaning.ipynb` and `03_eda_exploration.ipynb` as supporting work that gets consolidated. This prevents the common fail where the notebook only runs from a subfolder with `../data` paths or where findings exist only in fragments.

Considered Options: Keep everything in `notebooks/` only; or require three separate deliverable notebooks.
Consequences: Eman must copy consolidated cleaning + analysis into the Main Notebook before submission and re-run it top-to-bottom from the repo root; review checks `Superstore_Analysis.ipynb` exists (checklist item 2).
