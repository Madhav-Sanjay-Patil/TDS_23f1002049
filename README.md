- **Data Collection**: This data was scraped from the GitHub API, focusing on GitHub users based in Berlin with over 200 followers as of 2024-10-31. Information gathered includes user details and up to 500 recent repositories per user, providing a comprehensive view of their activity.

- **Key Finding**: Analysis shows that developers who maintain detailed project documentation tend to have more engagement on their repositories. This correlation highlights the importance of accessible information for fostering user interest and interaction with open-source projects.

- **Recommendation**: To enhance user engagement and ensure project clarity, developers are encouraged to enable both wikis and project sections within their repositories. These features offer structured resources and insights, making projects more user-friendly and attracting more community contributions.

# GitHub Users in Berlin

This repository contains data about GitHub users in Berlin with over 200 followers and their repositories.

## Files

1. `users.csv`: Contains information about 610 GitHub users in Berlin with over 200 followers
2. `repositories.csv`: Contains information about 60,995 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 200+ followers
- Up to 500 most recently pushed repositories per user
