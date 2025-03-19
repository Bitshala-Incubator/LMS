# Open Source Learning Management System for Bitcoin Technical Cohorts

## Overview 📚

The **Learning Management System (LMS)** will automate and improve study cohorts. Organizations like Bitshala, Btrust, B40S, and Vinteum currently use manual workflows. These are slow and inefficient.

This platform will let candidates access study materials and exercises. It supports guided and self-paced learning. The backend will handle tracking, scoring, forums, and skill discovery.

The LMS will be a shared tool for managing candidate pools. Organizations can also merge pools if needed. The project will deliver a web app with a simple frontend and a powerful backend. It will be open-source under the MIT License.

### Key Features ✨
- **Automated Workflows**: Reduces manual tasks for cohort management.
- **Self-Paced Learning**: Tracks for independent progress.
- **Centralized Database**: Stores participant and activity data.
- **Simple Interface**: Easy to use and navigate.
- **Community Features**: Enables collaboration and solution sharing.
- **Admin Tools**: Provides analytics and management options.
- **Integration**: Works with other education platforms.

---

## Requirements 🛠️

### Product Features
This section lists the main features needed for a smooth user experience.

- **Clear UX Flow**: Simple and intuitive navigation.
- **Profile Section**: Users can add and update personal details.
- **Integrations**: Support for Discord and GitHub Classroom.
- **Evaluation Tools**: Handle both descriptive and objective questions.
- **Community Page**: Connect participants and encourage collaboration.
- **Notice Board**: Show upcoming events and updates.

---

## Pages and Functionalities 🌐

### Landing Page 🏠
The landing page introduces the platform and its features.

- **Purpose**: Explain the platform's benefits.
- **Content**:
  - Join self-paced tracks.
  - Explore the community.
  - Collaborate with others.
  - View live updates on cohorts and events.

### Sign-Up Page 🔑
The sign-up page handles user authentication.

- **Authentication**:
  - Sign In, Sign Up, Forgot Password.
  - OAuth with Google and GitHub.
- **Fields**:
  - Email, Password, Display Name (optional).
  - Email verification.

### Home Page 🏡
The home page is the user dashboard.

- **Dashboard**:
  - Current progress and status.
  - Profile button (details, skills, links, etc.).
  - App walkthrough (v0.1.1).
  - Community link.
  - Important updates.

### Profile Page 👤
The profile page manages user details.

- **Details**:
  - Name, Display Picture, Email.
  - Discord, GitHub, Social Links.
  - Additional details (e.g., BOSS Score).
  - Security settings.

### Tracks 📖
Tracks are the main learning modules.

- **Available Tracks**:
  - MB, PB, LBTCL, BPD (LN, NOSTR, and more).
- **Structure**:
  - Chapters with:
    - Summary.
    - Study links and resources.
    - Knowledge tests.
  - After two chapters:
    - Code challenges (GitHub Classroom).
    - Submission status and scores.
    - Community solutions.
    - Discord celebration posts (v0.1.2+).

### Community Page 🌍
The community page connects participants.

- **Features**:
  - Monthly leaderboard.
  - Filters for skills, projects, and interests.
  - Event highlights.
  - Add your own events.
  - Discussion forum.
  - Project showcase (e.g., [Dev.to](https://dev.to/)).

### Admin Page 🛡️
The admin page provides management tools.

- **Tools**:
  - Live analytics for participants.
  - Review solutions and export data.
  - Force resubmissions.
  - Block users and delete posts.

---

## Development Workflow 🚀

A simple workflow ensures smooth collaboration.

- Use **GitHub Issues** for tasks.
- Open an issue for each page with:
  - Figma links.
  - Notes for developers.
- Developers:
  - Take issues, link PRs, and track tasks in the GitHub PM board.
