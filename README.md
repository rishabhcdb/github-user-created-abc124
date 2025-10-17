# GitHub User Account Creation Date Display

## Overview

This project provides a simple Bootstrap webpage that allows users to retrieve and display the creation date of a GitHub account. It uses a form to accept a GitHub username, fetches the account information from the GitHub API, and presents the creation date in a user-friendly format. The application optionally supports using a GitHub API token for increased rate limits.

## Features

*   **GitHub Username Input:** Accepts a GitHub username via a form with the ID `github-user-abc124`.
*   **Account Creation Date Display:** Displays the account creation date in YYYY-MM-DD UTC format within an element with the ID `github-created-at`.
*   **GitHub API Integration:** Fetches user data from the GitHub API using `https://api.github.com/users/`.
*   **Token Authentication (Optional):** Supports using a GitHub API token via the `?token=` query parameter to increase API rate limits.
*   **Bootstrap Styling:** Uses Bootstrap for a clean and responsive user interface.

## How to Use

1.  Open the `index.html` file in your web browser.
2.  Enter the GitHub username in the form field.
3.  Optionally, append `?token=[YOUR_GITHUB_TOKEN]` to the URL to use a GitHub API token. Replace `[YOUR_GITHUB_TOKEN]` with your actual token.
4.  The account creation date will be displayed below the form.

## Technology Stack

*   HTML
*   CSS (Bootstrap)
*   JavaScript
*   GitHub API

## Project Structure

```
.
├── index.html
└── README.md
```

## Local Development

1.  Clone the repository: `git clone https://github.com/your-username/github-user-created-abc124.git` (Replace `your-username` with your GitHub username).
2.  Open `index.html` in your browser.

## License

This project is licensed under the MIT License.

---

## Round 2 Enhancement
**Updated:** 2025-10-17

### New Feature
Show an aria-live alert #github-status that reports when a lookup starts, succeeds, or fails.

### Implementation
- Updated with new functionality
- All Round 1 features remain intact
