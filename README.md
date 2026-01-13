📘 Version Control with Git – Final Project
This project simulates a team developing and releasing a product using the Gitflow workflow.
It follows a structured branching model with feature, release, and hotfix branches, including merges, rebases, conflict resolutions, and tagging.

🚀 Project Objective
Create a Git repository that replicates the commit graph and commit details provided in the assignment.
The workflow includes:

Initial setup and README creation on master
Development work on develop
Building Feature 1
Creating and merging a Release branch (v1.00)
Creating and merging a Hotfix branch (v1.01)
Rebase operations on Feature 2 (including conflict resolution)


🧱 Branch Structure
This project uses the Gitflow branching model:

master – Stable production-ready state
develop – Integration branch for ongoing development
feature/feature1 – Development of feature 1
feature/feature2 – Development of feature 2
release/release1 – Pre‑production release v1.00
hotfix/hotfix1 – Post-release patch v1.01


🧩 Commit Overview
Your repository should include commits matching the assignment’s table and graph.
✔ Key Commits

A — Add README.md (master)
B — Add fileA.txt (develop)
C — Feature 1 WIP
D — Feature 1 with 2 bugs
E — Merge feature1 → develop
G — Fix feature 1 bug (release1)
H — Merge release1 → master (tag: v1.00)
I — Merge release1 → develop
K — Hotfix: fix feature 1 bug (hotfix1)
L — Merge hotfix1 → master (tag: v1.01)
M — Merge hotfix1 → develop
F1 / F2 — Feature 2 rebase with conflict resolution


🏷 Tags

v1.00 — Created after merging release1 into master
v1.01 — Created after merging hotfix1 into master


🔧 Instructions to Validate
Anyone reviewing your project should:

Clone your repository
Examine the commit history graph (git log --graph --oneline --all)
Verify branches, merges, rebases, and tags match the assignment


📄 Notes
This project is based on the Atlassian GitFlow exercise (© 2018 Atlassian).
