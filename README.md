# West_Managment

A modern Waste Management UI project that showcases a complete product journey — from onboarding and login to AI waste scanning, recycling guidance, leaderboard, and community analytics.

This repository is designed as a clean front-end reference for eco-tech applications, with structured screen flows and ready-to-open HTML prototypes.

## Project Overview

`West_Managment` presents a polished multi-screen interface for a waste tracking and recycling platform.  
The experience is split into clear phases:

- Onboarding and introduction
- Authentication
- Core mobile app screens
- Community/web dashboard analytics

The root `index.html` works as a structured navigator that links each screen in the correct sequence.

## Highlights

- Clean and organized project structure
- Responsive HTML/CSS entry page for navigation
- Multiple UI prototype screens grouped by product flow
- Tailwind-powered design screens with modern visual language
- Ready for extension into a full web or mobile app workflow

## Tech Stack

- HTML5
- CSS3
- Tailwind CSS (via CDN in screen files)
- Google Fonts + Material Symbols

## Folder Structure

```text
West_Managment/
├── index.html
├── README.md
├── assets/
├── css/
│   └── style.css
├── screen-0/
│   ├── code.html
│   └── screen.png
├── screen-1/
│   ├── code.html
│   └── screen.png
├── screen-2/
│   ├── code.html
│   └── screen.png
├── screen-3/
│   ├── code.html
│   └── screen.png
├── screen-4/
│   ├── code.html
│   └── screen.png
├── screen-5/
│   ├── code.html
│   └── screen.png
├── screen-6/
│   ├── code.html
│   └── screen.png
└── screen-7/
    ├── code.html
    └── screen.png
```

## Screen Flow

### 1) Onboarding
- `screen-0`: Splash screen
- `screen-1`: Intro / feature walkthrough

### 2) Authentication
- `screen-2`: Login UI

### 3) Core App (Mobile)
- `screen-3`: Home dashboard
- `screen-4`: AI waste scanner + result modal
- `screen-5`: Recycling guide
- `screen-7`: Leaderboard and gamification

### 4) Community / Web Dashboard
- `screen-6`: Community analytics, schedules, and map-style monitoring

## How to Run

Because this is a static front-end prototype project, no build step is required.

### Option A: Open directly
1. Open `index.html` in your browser.
2. Use the screen cards to open individual pages.

### Option B: Use VS Code Live Server (recommended)
1. Open the project in VS Code.
2. Install the **Live Server** extension (if not already installed).
3. Right-click `index.html` → **Open with Live Server**.

## Why This Project Is Useful

- Great starting point for hackathons and college projects in sustainability tech
- Can be converted into React/Vue/Next.js screens quickly
- Useful as a UI baseline for adding backend services (auth, scan APIs, analytics)
- Demonstrates product storytelling through structured screen flow

## Next Improvements (Optional)

- Convert static screens into reusable components
- Add real navigation and routing
- Integrate camera/file upload for real AI scanning
- Connect leaderboard and stats to backend APIs
- Add dark mode state handling and interaction logic

## Author

Maintained by **Hansaliya Shyam**.

If you want, this README can be further upgraded with badges, preview GIFs, architecture diagrams, and deployment instructions.