# GitHub User Data Repository

This repository contains data about GitHub users from Berlin with over 200 followers and their public repositories.

## Overview

The dataset includes two primary files:
- **`users.csv`**: Contains user information, including their GitHub username, full name, company, location, email, hireable status, bio, public repositories count, followers count, following count, and the date they joined GitHub.
- **`repositories.csv`**: Contains information about the public repositories owned by the users, including the repository's full name, creation date, number of stars, number of watchers, programming language used, and whether the repository has projects or a wiki enabled.

## Files

- **`users.csv`**: 
  - **Columns**:
    - `login`: GitHub user ID
    - `name`: Full name of the user
    - `company`: Company the user works at (cleaned and formatted)
    - `location`: City of the user
    - `email`: User's email address
    - `hireable`: Whether the user is open to hiring
    - `bio`: A short bio of the user
    - `public_repos`: Number of public repositories
    - `followers`: Number of followers
    - `following`: Number of people the user follows
    - `created_at`: Date when the user joined GitHub

- **`repositories.csv`**:
  - **Columns**:
    - `login`: GitHub user ID of the owner
    - `full_name`: Full name of the repository
    - `created_at`: Date when the repository was created
    - `stargazers_count`: Number of stars the repository has received
    - `watchers_count`: Number of watchers on the repository
    - `language`: Programming language the repository is written in
    - `has_projects`: Whether the repository has projects enabled
    - `has_wiki`: Whether the repository has a wiki
    - `license_name`: Name of the license under which the repository is available

## Usage

You can use the provided CSV files for analysis of GitHub users and their repositories. The data can help identify trends in programming languages, user engagement, and other metrics relevant to the GitHub community.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

