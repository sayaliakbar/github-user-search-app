# Frontend Mentor - GitHub User Search App

This repository contains my solution to the [GitHub user search app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/github-user-search-app-Q09YOgaH6). The application allows users to search for GitHub profiles by username, displaying relevant information fetched from the GitHub Users API. Key features include a responsive design, light and dark theme toggle, and dynamic error handling.

## Table of Contents

- [Overview](#overview)
  - [Features](#features)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Process](#process)
  - [Built With](#built-with)
  - [Key Learnings](#key-learnings)
- [Usage](#usage)
- [Areas for Improvement](#areas-for-improvement)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

### Features

- Search GitHub users by username.
- Display user information, including:
  - Full name and username.
  - Avatar image.
  - Join date.
  - Bio.
  - Repository, follower, and following counts.
  - Links to Twitter, company, and website (if available).
  - Location.
- Responsive error handling for non-existent users.

---

### Screenshot

#### Desktop View

![github-user-search-app-desktop](https://github.com/user-attachments/assets/433ae913-bb33-4d8b-ac62-28405a8be058)

#### Desktop View (Dark Mode)

![github-user-search-app-desktop-darkMode](https://github.com/user-attachments/assets/6ec0b9aa-714a-4973-a1c5-e8cf2bc680e4)

#### Active States

![github-user-search-app-desktop-activeStates](https://github.com/user-attachments/assets/0a446848-b7be-491d-94bd-0f4d12851ae1)

#### Tablet View

![github-user-search-app-tablet](https://github.com/user-attachments/assets/2cf8e641-a499-4cf9-9729-24b099336745)

#### Mobile View

![github-user-search-app-mobile](https://github.com/user-attachments/assets/491c25c5-7c45-467d-ae05-9497d999ee89)

---

### Links

- **Live Site URL**: [Visit the live demo](https://perfect-bun.surge.sh/)

---

## Process

### Built With

- **HTML5**: Provides a semantic structure for the application.
- **Tailwind CSS**: To style and organize the layout.
- **JavaScript**: Handles interactivity, API calls, and DOM updates.

---

### Key Learnings

This project enhanced skills in:

- **API Integration**:  
  Using the `fetch` API to retrieve and display real-time data from the GitHub API.

- **Error Handling**:  
  Managing HTTP errors, such as 404 responses, to display user-friendly messages.

- **DOM Manipulation**:  
  Dynamically updating the UI based on fetched data using JavaScript methods like `querySelector`, `classList`, and `innerHTML`.

- **Date Formatting**:  
  Transforming the `created_at` field from ISO format to a user-friendly format.

- **Responsive Design**:  
  Ensuring proper alignment and layout across various screen sizes.

---

## Usage

1. Enter a GitHub username in the search bar.
2. Press "Search" to fetch and display the user details.
3. If the user is not found, an error message will be displayed.

---

## Areas for Improvement

- **Design**: Enhance the UI with better styling and responsiveness using Tailwind CSS or custom CSS.
- **Accessibility**: Improve keyboard navigation and implement `aria-*` attributes.
- **Functionality**:
  - Add pagination for repositories.
  - Include additional user details like starred repositories.
  - Implement a dark mode toggle.

---

## Author

- GitHub: [@sayaliakbar](https://github.com/sayaliakbar)
- LinkedIn: [@sayaliakbar](https://linkedin.com/in/sayaliakbar)

---

## Acknowledgments

- [GitHub API Documentation](https://docs.github.com/en/rest)
- [MDN Web Docs](https://developer.mozilla.org/en-US/) for JavaScript reference and tutorials.
- [Frontend Mentor community](https://www.frontendmentor.io/) for their helpful resources and encouragement.

