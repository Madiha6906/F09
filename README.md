<div align="center">

#  The 12th Man

### An Interactive Simulation on Equality, Prejudice & Discrimination



</div>

---

##  Overview:

**The 12th Man** is a browser-based interactive simulation built around a cricket team selection story. It walks users through how **prejudice** and **discrimination** creep into decision-making — and what it takes to restore **equality**.

> *"Prejudice creates unfair assumptions. Discrimination creates unequal opportunities. Equality ensures everyone is judged by their abilities and efforts."*

---

##  Story Architechture:

The simulation is structured across **5 scenes**, each representing a key concept:

| # | Scene | Core Concept | What Happens |
|---|-------|--------------|--------------|
| 1 | **Equality** | Fair Start | Every player enters trials expecting to be judged on ability |
| 2 | **Prejudice** | Bias Enters | Personal assumptions begin to influence the selection discussion |
| 3 | **Discrimination** | Unfair Exclusion | A strong performer is left out of the squad despite good trial results |
| 4 | **Consequences** | The Cost of Bias | The team struggles — the excluded player's skills were exactly what was needed |
| 5 | **Equality Restored** | Reform | Selections are moved to a performance-only, data-driven process |

---

##  Learning Objectives:

By the end of this simulation, users will be able to:

- Distinguish between **prejudice** (unfair assumption) and **discrimination** (unfair action)
- Understand how bias harms both **individuals** and **teams**
- Recognise what **genuine equality of opportunity** looks like
- Reflect on their own decision-making through interactive choices

---

##  Project Structure:

```
the-12th-man/
│
├── index.html                  # Landing page
├── README.md                   # Project documentation
├── storyboard.jpeg             # Original storyboard reference
│
├── scenes/
│   ├── scene1-equality.html
│   ├── scene2-prejudice.html
│   ├── scene3-discrimination.html
│   ├── scene4-consequences.html
│   └── scene5-restored.html
│
├── assets/
│   ├── images/                 # Character and scene illustrations
│   └── audio/                  # Narration / ambient sound (optional)
│
├── js/
│   ├── simulation.js           # Core simulation logic
│   ├── choices.js              # Decision tree and branching
│   └── scoring.js              # Fairness score tracker
│
├── css/
│   ├── main.css                # Global styles
│   └── scenes.css              # Scene-specific layout
│
└── data/
    └── dialogue.json           # All character dialogue and choices
```

---

## Getting Started:

### Prerequisites
- Any modern browser — Chrome, Firefox, Edge, Safari
- No installation needed for the browser version
- Node.js v18+ *(optional, for local dev server)*

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/your-username/the-12th-man.git

# 2. Move into the project folder
cd the-12th-man

# 3a. Open directly in browser
open index.html

# 3b. OR serve with a local server
npx serve .
# then visit http://localhost:3000
```

---

##  How It Works

1. **Pick a role** — Play as the Head Selector, the New Player, or observe as the Coach
2. **Work through each scene** — Read dialogue and make decisions at key branching points
3. **Watch the impact** — Your choices affect team performance and a live **Fairness Score**
4. **Debrief at the end** — A summary maps your decisions to real-world concepts of equality and discrimination

---

##  Tech Stack

| Layer | Technology |
|-------|------------|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | JavaScript (ES6+) |
| Data | JSON |
| Hosting | GitHub Pages *(planned)* |

---

##  Roadmap

- [x] Storyboard finalised
- [x] README and project structure defined
- [ ] Scene layouts (HTML/CSS)
- [ ] Dialogue JSON populated
- [ ] Decision branching logic
- [ ] Fairness Score system
- [ ] Mobile responsiveness
- [ ] Accessibility (ARIA, keyboard nav)
- [ ] GitHub Pages deployment
- [ ] Facilitator/teacher guide

---

##  Contributing

1. Fork the repository
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "Add: your description"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

##  License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
Work under progress..
</div>

