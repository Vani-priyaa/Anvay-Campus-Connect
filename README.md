# Anvay — Campus Connect

Anvay is a campus community concept designed to help students connect with mentors, discover faculty-led project opportunities, and collaborate with peers.

> **Repository note:** This is a reconstructed, GitHub-ready demo based on the project description and features previously documented. The original source files were unavailable. This repository should not be represented as the recovered original codebase.

## Core experience

- **College email gate:** Demo entry accepts email addresses ending in `@svecw.edu.in`.
- **Mentor discovery:** Browse sample mentor profiles, search by name/expertise, and filter by domain.
- **Project board:** Explore sample project ideas, search by skills, and filter by domain.
- **Share an idea:** Add a project idea to the board.
- **Local demo persistence:** New project ideas are stored in the browser using `localStorage`.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage` and `sessionStorage`

## Run locally

No build tools or package installation are required.

1. Download or clone this repository.
2. Open `index.html` in a browser.
3. Enter a name and an email ending in `@svecw.edu.in`.
4. Explore mentors and projects, or add a project idea.

For the best experience, use a current version of Chrome, Firefox, or Edge.

## Important implementation notes

- The sign-in screen is a **demo email-domain check**, not production authentication.
- Mentor profiles and initial project ideas are sample/demo content.
- Connection requests display demo feedback; they are not sent to real mentors.
- Project ideas added in the browser are stored locally on that device.
- The original project was described as using Firebase Authentication and Firebase Database. The original Firebase configuration and source files were not available for this reconstruction, so Firebase is **not connected in this repository**.
- Do not add Firebase credentials, private keys, or other secrets to a public repository.

## Suggested next steps before presenting this as a live product

1. Create a Firebase project and configure Authentication with the college email-domain restriction enforced by trusted backend/security rules.
2. Replace demo session handling with Firebase Authentication.
3. Replace local demo data with Firestore collections and appropriate security rules.
4. Add real mentor/project records only with permission from the people represented.
5. Deploy the verified version and update this README with the live URL.

## Project context

The project concept focuses on:
- mentorship matching between students and mentors,
- faculty-led project boards,
- a campus-restricted community using college email addresses.

When describing your personal contribution on a resume, list only the work you personally completed and can explain confidently.
