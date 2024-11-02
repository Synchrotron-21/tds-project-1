- Data was scraped from the GitHub API by filtering users in Stockholm with over 100 followers and fetching their most recent repositories.
- A significant portion of repositories in Stockholm are written in JavaScript but surprisingly TypeScript is also seen in many repositories.
- Developers in Stockholm should focus on collaboration in JavaScript-based and Python-based projects to leverage the local expertise and community.

# GitHub Users in Stockholm

This repository contains data about GitHub users in Stockholm with over 100 followers and their repositories.

## Files

1. `users.csv`: Contains information about 410 GitHub users in Stockholm with over 100 followers
2. `repositories.csv`: Contains information about 35432 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data
4. `tds_project_1_QS.ipynb`: Python script used for questions 1 to 16

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 100+ followers
- Up to 500 most recently pushed repositories per user
