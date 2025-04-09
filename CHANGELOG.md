[v1.0.0] - 09-04-2025
Initial Release of Student Feedback Manager


Features
feedback_entry.py
Collects student feedback via a simple input interface.

score_calculator.py
Calculates average feedback score based on submitted values.


CI/CD
Integrated GitHub Actions Workflow:

Automatically installs dependencies

Runs pytest on each push or pull request to the main branch


Documentation
Added README.md
Added LICENSE
Added Release notes 

[v1.0.1] - 09-04-2025

Added feedback_summary.py
top_scores(feedback_list, top_n=3)
Returns the top N feedback scores (default is top 3).

grade_wise_count(feedback_list)
Categorizes feedback scores into grade buckets:

A (≥ 4.5)

B (3.5–4.49)

C (2.5–3.49)

D (< 2.5)

Documentation
Updated README.md:

New section describing feedback summary functionality

Examples of grading and score breakdown

Pull Request
Merged feature/summary into main via Pull Request:

Includes new file, tests, and doc updates

Passed all GitHub Actions test checks
