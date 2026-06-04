 The 12th Man — Interactive Simulation
> *"Equality is achieved when opportunities are based on ability and effort rather than assumptions."*
An interactive educational simulation based on the storyboard "The 12th Man" — a cricket team selection scenario that explores the concepts of Equality, Prejudice, Discrimination, and their real-world consequences.
---
 About the Project
The 12th Man is a browser-based simulation designed to help users understand how bias and prejudice can affect decision-making — even in seemingly merit-based processes like sports team selection. Players step into the roles of selectors, players, and coaches, experiencing the ripple effects of fair and unfair choices.
The simulation is built around a 5-scene narrative arc derived from the original storyboard:
Scene	Theme	Description
1	Equality	Every player enters trials expecting to be judged fairly on ability
2	Prejudice	Personal assumptions begin to influence the selection discussion
3	Discrimination	A strong performer is excluded from the squad without merit-based justification
4	Consequences	The team suffers — the excluded player's skills are exactly what was needed
5	Equality Restored	Selections are reformed to be based solely on performance and trial results
---
 Learning Objectives
By engaging with this simulation, users will:
Understand the difference between prejudice (an unfair assumption) and discrimination (an unfair action)
See how bias-driven decisions harm both individuals and teams/organisations
Recognise what true equality of opportunity looks like in practice
Reflect on their own decision-making through interactive choices
---
 Project Structure
```
the-12th-man/
│
├── index.html              # Entry point / landing page
├── README.md               # Project documentation (this file)
│
├── /scenes                 # Individual simulation scenes
│   ├── scene1-equality.html
│   ├── scene2-prejudice.html
│   ├── scene3-discrimination.html
│   ├── scene4-consequences.html
│   └── scene5-restored.html
│
├── /assets
│   ├── /images             # Storyboard panels, character illustrations
│   ├── /audio              # (Optional) Narration or ambient sound
│   └── /storyboard         # Original storyboard reference images
│
├── /js
│   ├── simulation.js       # Core simulation logic and state management
│   ├── choices.js          # Decision-tree and branching logic
│   └── scoring.js          # Fairness/bias score tracker
│
├── /css
│   ├── main.css            # Global styles
│   └── scenes.css          # Scene-specific layout and animations
│
└── /data
    └── dialogue.json       # All character dialogue and choice options
```
---
 Getting Started
Prerequisites
A modern web browser (Chrome, Firefox, Edge, Safari)
No installation required for the browser version
(Optional) Node.js v18+ if running a local dev server
Running Locally
```bash
# Clone the repository
git clone https://github.com/your-username/the-12th-man.git

# Navigate into the project
cd the-12th-man

# Option 1: Open directly in browser
open index.html

# Option 2: Serve with a local server (recommended)
npx serve .
# or
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.
---
 How the Simulation Works
Choose your role — Play as the Head Selector, the New Player, or observe as a neutral Coach.
Navigate each scene — Read dialogue, observe situations, and make decisions at key branching points.
See the impact — Your choices affect team morale, performance outcomes, and a Fairness Score.
Reflect at the end — A debrief summarises what happened and maps it to real-world concepts of equality and discrimination.
Key Concepts Modelled
Prejudice creates unfair assumptions — shown in Scene 2 when selectors let familiarity override merit.
Discrimination creates unequal opportunities — shown in Scene 3 when a qualified player is excluded.
Equality ensures everyone is judged by ability and effort — achieved in Scene 5 through policy reform.
---
 Tech Stack
Layer	Technology
Structure	HTML5
Styling	CSS3 / Tailwind CSS
Logic	Vanilla JavaScript / React (TBD)
Dialogue Data	JSON
Hosting	GitHub Pages (planned)
---
 Storyboard Reference
The simulation is directly adapted from the following storyboard panels:
![The 12th Man Storyboard](storyboard.jpeg)
The five panels serve as the scene design blueprint for each stage of the simulation.
---
 Contributing
Contributions are welcome! If you'd like to improve the simulation, add new scenarios, or translate it:
Fork the repository
Create a feature branch: `git checkout -b feature/your-feature-name`
Commit your changes: `git commit -m "Add: description of change"`
Push to your branch: `git push origin feature/your-feature-name`
Open a Pull Request
Please follow the Code of Conduct in all interactions.
---
 Roadmap
[x] Storyboard finalised
[x] README and project structure defined
[ ] Scene 1–5 HTML/CSS layout
[ ] Dialogue JSON populated
[ ] Decision branching logic
[ ] Fairness Score system
[ ] Mobile responsiveness
[ ] Accessibility (ARIA labels, keyboard navigation)
[ ] GitHub Pages deployment
[ ] Teacher/facilitator guide PDF
---
 License
This project is licensed under the MIT License.
---
 Author
Created as part of an educational design project.  
Inspired by real-world issues of fairness, inclusion, and equal opportunity in sports and beyond.
---
> *"Prejudice creates unfair assumptions. Discrimination creates unequal opportunities. Equality ensures everyone is judged by their abilities and efforts."*  
> — The 12th Man
