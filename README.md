Elite Rummy Circle - Release Notes
Project Overview
Elite Rummy Circle is a real-time, cloud-synced scoring application designed for competitive league play. Transitioned from a local-storage prototype to a Firebase-backed multi-user platform.
Version 15.0 (Current Production)
Dynamic Player Management: Added the ability to add and remove player slots during match setup.
Safety Constraints: Enforced a minimum of two players for game integrity while allowing the removal of accidental "ghost" rows via a new ✕ delete button.
UI Polish: Refined the "New Match" screen for better alignment and button spacing.
Version 14.0
Timestamp Integration: Added a "🕒 Add Date & Time" feature to match names for accurate session logging.
Sidebar Evolution: Renamed the roster to "Players" and implemented individual Live Status Lights (Green) next to each registered user.
UX Update: Clarified the Match Name input with the "Enter Match Name" placeholder.
Version 13.0
Security Lockdown: Completely removed the Developer Login bypass to ensure production security.
Production Hardening: Locked authentication to verified Email/Password and Google Sign-In protocols only.
Version 12.0 - 10.0 (The "Glass" Era)
Glassmorphism UI: Overhauled the interface with a "Frosted Glass" aesthetic—semi-transparent panels, background blurring, and a brighter teal-tinted background.
Live Sidebar Roster: Integrated a real-time sidebar that displays all registered users in the "Elite Rummy Circle" community.
Logout Optimization: Fixed a "flicker" glitch by ensuring the app resets to the home login screen immediately upon sign-out.
Version 9.0 - 1.0 (The Foundation)
Firebase Integration: Switched from browser local storage to Firestore Cloud Database for real-time syncing across all devices.
Authentication Suite: Built dedicated Login and Sign-Up screens supporting both Email/Password and Google Sign-In.
Viking Alias Generator: Added a fun "Valhalla" gamification element that assigns a random Viking name (e.g., Thor Bloodaxe) to new users.
Core Scoring Engine: Developed the logic for Rummy-specific actions: SHOW, FC (Full Count), DROP (20 pts), and OUT (240 pts).
Real-Time Sync: Implemented "Snapshot Listeners" so every player sees score changes instantly as they happen.
Technical Stack
Frontend: HTML5, CSS3 (Glassmorphism), Vanilla JavaScript.
Backend: Firebase Authentication, Cloud Firestore.
Hosting: GitHub Pages.
