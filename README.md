Website Lock (In Progress)
Website Lock is a browser extension designed to help users manage access to certain websites through password protection. It allows users to lock websites by URL, providing the ability to set time limits, password protection, and secure storage options. The project is in development and aims to give users more control over their browsing experience by integrating a user-friendly interface with strong security practices.

Table of Contents
Project Overview
Features
Technical Stack and Tools
Installation
Development Steps
Security Measures
Future Features
Contributing
License
Project Overview
Website Lock allows users to lock access to specific websites, requiring password authentication to gain access. Users can manage which websites are locked, set time limits for temporary access, and configure other settings through a control panel interface.

This project is designed to:

Help manage distractions by blocking access to certain websites.
Ensure privacy and control with password-protected websites.
Implement robust security with encryption and other modern practices.
Features
Website Selection: Users can select websites to lock by entering URLs or choosing from a list of popular websites using a checkbox.
Password Protection: Users set a password to lock and unlock websites. Additional features like password strength indicators, recovery options, and two-factor authentication will be included.
Custom Block Page: When attempting to visit a locked site, users will see a custom block page with a password prompt.
Timeout Feature: Users can unlock websites temporarily, with automatic re-locking after a specified period.
Control Panel: Manage locked websites, change passwords, and configure additional settings via an easy-to-use interface.
Secure Data Storage: Locked websites and user passwords are stored securely using encryption.
Technical Stack and Tools
Frontend (UI for control panel and password prompts)
HTML, CSS, JavaScript: Core technologies for building the user interface.
Frontend Framework: React, Vue, or plain JavaScript depending on the final design choice.
Backend (Optional, if needed for account storage and password management)
Node.js/Express: To handle authentication if the user’s lock data needs to be shared across multiple devices.
LocalStorage/IndexedDB: For client-side storage of locked websites and settings.
Browser Extension APIs
Chrome Extension API / Firefox WebExtension API: To build the browser extension that blocks website access.
chrome.webRequest.onBeforeRequest: Intercept and block website requests.
Security Tools
crypto-js: For encryption and secure storage of passwords and website lists.
