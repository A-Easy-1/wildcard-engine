# wildcard-engine
Mobile-friendly web application for a golf match play trip that dynamically generates a simulated player persona ("Rex 'The Wildcard' Harper"), calculates multi-factor round outcomes, and generates 18-hole handicap scorecards for 5 courses.


# ⛳️ The Estero Cup — Rex "The Wildcard" Harper Engine

An interactive, mobile-optimized web application designed for group golf trips to handle a simulated "Ghost/Wildcard" player in match play formats. The engine dynamically combines randomized pre-round factor spins to determine the Wildcard player's performance tier, then builds custom, hole-by-hole scorecards mapped directly to real course handicap data.

---

## 🌟 Features

* **Interactive Spin Wheels:** Spin for **Rest**, **Vibes**, and **Beverages** independently to build suspense before revealing the round outcome.
* **Weighted Persona Logic:** Pre-round factor scores compound dynamically with slight RNG variance to determine Rex's overall finish (from Rank #1 Jackpot down to Rank #8 Bust).
* **Multi-Course Routing Engine:** Built-in stroke allocation tables, par ratings, and handicap rankings ($HDCP \le 10$) for 5 courses:
  * Hammock Bay
  * The Rookery
  * The Park
  * Saltleaf Preserve
  * Tiburón Black
* **Intelligent Scorecard Generator:** Input Rex's target net score post-round, and the engine automatically:
  * Converts Net to Gross based on his 10 Course Handicap.
  * Ensures his narrative **Magic Moment** (birdie/eagle) and **Blow-Up Hole** occur on the exact holes revealed in his backstory.
  * Highlights stroke holes (`•`) and magic/blow-up holes visually in the table.
* **Format Selector Support:** Built for 2-Man Net Best Ball (Rounds 1–3) and Singles Match Play (Rounds 5 & 7).

---

## 👤 Persona Profile: Rex "The Wildcard" Harper

* **Handicap:** 10
* **Style:** Dripped out in exclusive private club logos and tour-issue gear.
* **Signature Quirk:** Carries two putters in his bag (one blade, one mallet) depending on green speeds and vibes.
* **Playing Profile:** Pure 10-handicap stick who swings between shooting a smooth 74 with ease or ballooning to a 102 when his lethal two-way miss off the tee takes over.

---

## 🚀 Getting Started

No build tools, package managers, or dependencies required!

### Local Usage
1. Download or clone this repository.
2. Open `index.html` in any web browser (Safari, Chrome, Firefox, Edge).

### GitHub Pages Deployment
1. Push this repository to your GitHub account.
2. Go to **Settings > Pages**.
3. Under **Source**, choose **Deploy from a branch** and select `main` (or `master`) `/ (root)`.
4. Access the live web app on any device via your GitHub Pages URL:
   `https://<your-username>.github.io/<repo-name>/`

---

## 🛠 Tech Stack

* **HTML5** (Semantic structure & inline data bindings)
* **CSS3** (Flexbox/Grid layout, dark mode aesthetic, mobile touch targets)
* **Vanilla JavaScript (ES6)** (Weighted logic engine, course score routing, DOM manipulation)
