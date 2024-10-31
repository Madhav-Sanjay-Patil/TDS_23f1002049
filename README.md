- Data was scraped from the GitHub API for users in Berlin with over 200 followers as of 2024-10-31.
- Analysis revealed that developers with project documentation often have higher engagement through repositories.
- Developers should enable both wikis and project sections on their repositories to boost user engagement and project clarity.

# GitHub Users in Berlin

This repository contains data about GitHub users in Berlin with over 200 followers and their repositories.

## Files

1. `users.csv`: Contains information about 610 GitHub users in Berlin with over 200 followers
2. `repositories.csv`: Contains information about 60995 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 200+ followers
- Up to 500 most recently pushed repositories per user
