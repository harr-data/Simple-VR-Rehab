Simple VR rehabilitation System

An interactive web-based rehabilitation system designed to assess and improve motor control, reaction time, and cognitive memory skills through gamified test modules.

This project is built entirely using:
HTML
CSS
Vanilla JavaScript

No external libraries or frameworks are required.

Project Overview

The VR Rehabilitation System simulates neural training modules through three interactive test protocols:
Target Tracking (Balance Test)
Neural Reflex (Reaction Time Test)
Memory Sequence (Cognitive Test)

Each module runs for 15 seconds and generates performance metrics at completion.

Features
1. Target Tracking Protocol

Mouse-based balance simulation
Real-time cursor position tracking
Distance-from-center calculation
Stability index calculation

Performance metrics include:

Center Zone Time (%)
Maximum Deviation (px)
Stability Index (%)

2. Neural Reflex Protocol

Randomly spawning clickable targets
Real-time reaction time tracking
Accuracy calculation

Performance metrics include:

Total Targets Hit
Average Reaction Time
Fastest Response
Hit Accuracy (%)

3. Memory Sequence Protocol

Progressive memory challenge (Simon-style logic)
Increasing difficulty levels
Sequence tracking

Performance metrics include:

Maximum Level Reached
Sequences Completed
Accuracy (%)

How to Run

Download or clone the repository:
git clone https://github.com/your-username/vr-rehab-system.git


Open the project folder.

Open the file:

VR rehab.html


The application will run directly in your browser.

No installation or setup is required.

Project Structure
VR-Rehabilitation-System/
│
├── VR rehab.html   # Complete application (HTML + CSS + JavaScript)
└── README.md       # Project documentation


This project is built as a single self-contained HTML file containing:

Internal CSS styling

Embedded JavaScript logic

UI layout

State management system
Technologies Used
HTML5 – Structure
CSS3 – Styling and animations
JavaScript – Game logic, state management, performance tracking

Performance Tracking System

The system maintains a global state object to track:
Time remaining
Accuracy
Reaction speeds
Stability measurements
Memory progression

All metrics are dynamically calculated in real-time and displayed after each test session.

Possible Future Improvements

Persistent score saving using LocalStorage
User profiles
Data export (CSV)
Adjustable difficulty levels
Audio feedback
Responsive mobile layout
Integration with VR hardware

Educational Purpose

This project demonstrates:
DOM manipulation
Event handling
Timers and intervals
Game loop logic
UI state switching
Real-time performance calculations
Interactive interface design

Suitable for:

Web development mini projects
Human-computer interaction demonstrations
Cognitive training simulations
Rehabilitation interface prototypes

Author
Harrish Sivasubramanian

License
This project is open-source and free to use for educational purposes.
