# Portfolio Website Deployment Using GitHub Actions

## Overview

This project demonstrates how to build and deploy a simple portfolio website using:

* HTML
* CSS
* GitHub Actions
* GitHub Pages

The website contains three pages:

* Home
* About
* Contact

Whenever changes are pushed to the `main` branch, GitHub Actions automatically deploys the website to GitHub Pages.

---

## Project Structure

```text
portfolio-website/
│
├── index.html
├── about.html
├── contact.html
├── styles.css
│
└── .github/
    └── workflows/
        └── deploy.yml
```

---

## Features

* Responsive navigation menu
* Home page with profile information
* About page describing skills and goals
* Contact page with social links
* Automated deployment using GitHub Actions
* Hosted for free using GitHub Pages

---

## Technologies Used

| Technology     | Purpose             |
| -------------- | ------------------- |
| HTML           | Website structure   |
| CSS            | Styling             |
| Git            | Version control     |
| GitHub         | Source code hosting |
| GitHub Actions | CI/CD automation    |
| GitHub Pages   | Website hosting     |

---

## Deployment Workflow

```text
Developer Push
        │
        ▼
GitHub Repository
        │
        ▼
GitHub Actions Workflow
        │
        ▼
Build & Deploy
        │
        ▼
GitHub Pages
        │
        ▼
Live Website
```

---

## GitHub Actions Workflow

The workflow automatically:

1. Triggers on every push to the `main` branch.
2. Uploads website files.
3. Deploys the website to GitHub Pages.
4. Publishes the latest version online.

Workflow file:

```text
.github/workflows/deploy.yml
```

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/portfolio-website.git
```

### 2. Navigate to Project Directory

```bash
cd portfolio-website
```

### 3. Make Changes

Edit:

* index.html
* about.html
* contact.html
* styles.css

### 4. Commit Changes

```bash
git add .
git commit -m "Updated portfolio website"
git push origin main
```

### 5. Automatic Deployment

After pushing:

* GitHub Actions starts automatically.
* Website is deployed to GitHub Pages.

---

## Enable GitHub Pages

Navigate to:

```text
Repository → Settings → Pages
```

Under:

```text
Build and Deployment
```

Select:

```text
Source: GitHub Actions
```

---

## Access the Website

After successful deployment:

```text
https://YOUR_GITHUB_USERNAME.github.io/portfolio-website/
```

Example:

```text
https://johnsmith.github.io/portfolio-website/
```

---

## Future Enhancements

* Add project showcase section
* Add resume download button
* Add dark mode support
* Add contact form
* Add animations and transitions
* Add responsive mobile design
* Integrate custom domain

---

## Learning Outcomes

Through this project you will learn:

* Basic HTML and CSS
* Git and GitHub workflows
* CI/CD concepts
* GitHub Actions automation
* GitHub Pages deployment
* Static website hosting

---

## Author

**Madhuri**

Aspiring DevOps Engineer learning:

* Linux
* Git & GitHub
* Docker
* AWS
* GitHub Actions
* CI/CD
* Cloud Technologies

---

