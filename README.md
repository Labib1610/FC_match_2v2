# 🏆 Doubles Up — 2v2 Tournament Tracker 

A sleek, responsive web application designed to manage and track 2v2 round-robin tournaments where **everyone partners with everyone — once** . 

Built with pure HTML, CSS, and Vanilla JavaScript, **Doubles Up** automatically calculates mathematically optimal match pairings, keeps track of live scores, and dynamically updates a real-time leaderboard .

---

## 🚀 Live Demo

Check out the live application hosted on GitHub Pages:
### 👉 **[https://labib1610.github.io/FC_match_2v2/](https://labib1610.github.io/FC_match_2v2/)**

---

## ✨ Key Features

* **Dynamic 2v2 Round-Robin Scheduling:** Automatically generates match schedules utilizing custom disjoint matching algorithms so every player teams up with every other player exactly once .
* **Flexible Player Count:** Support for tournaments ranging between **4 to 10 players** .
* **Mathematical Coverage Indicator:** Calculates the total number of possible partnerships using the combination formula $\frac{N(N-1)}{2}$ . It instantly notifies you whether a perfect 1-time partnership coverage is mathematically possible or if one pairing must sit out .
* **Custom Avatars & Styling:** Features vibrant, auto-assigned color palettes for player avatars with custom initials and slick modern UI typography utilizing *Rajdhani* and *Inter* fonts .
* **Live Scorekeeper:** Interactive match cards equipped with stepper buttons (`+` / `-`) for quick score increments, instant winner highlighting, and visibility for players sitting out on byes .
* **Real-Time Leaderboard:** Instantly recalculates player stats after every point scored, featuring clickable column headers for custom sorting .
* **Champion Crowning:** Displays a visual progress bar tracking completed matches and unveils a celebration banner for the tournament champion once all matches are finalized .

---

## 📊 Leaderboard & Scoring System

The built-in leaderboard automatically ranks players based on their tournament performance using the following point distribution :

| Stat | Name | Description | Points Awarded |
| :--- | :--- | :--- | :---: |
| **W** | Wins | Number of matches won  | **+3 Pts** |
| **T** | Ties | Number of matches tied  | **+1 Pt** |
| **L** | Losses | Number of matches lost  | **0 Pts** |
| **PF** | Points For | Total points scored by the player's team | — |
| **PA** | Points Against | Total points conceded to opposing teams | — |
| **Diff** | Differential | Score differential ($PF - PA$) used as a tiebreaker | — |

---

## 🛠️ Built With

* **HTML5:** Semantic structure and accessible input controls .
* **CSS3:** Custom CSS variables, responsive CSS Grid/Flexbox layouts, and smooth keyframe animations .
* **Vanilla JavaScript (ES6+):** Custom shuffling algorithms, state management, and dynamic DOM manipulation without external libraries .

---

## 💻 How to Run Locally

Since this project requires no external backend or build tools, running it locally is effortless:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Labib1610/FC_match_2v2.git](https://github.com/Labib1610/FC_match_2v2.git)
