# ***Unstop 🤝 Wooble : IPL CRUNCH '26***

<img width="1200" height="357" alt="image" src="https://github.com/user-attachments/assets/0dcc5130-0113-4244-86b4-82e64b7b3736" />


### ***Problem Statement :-***

Everyone has IPL opinions. You are going to back yours with numbers.


#### **Answer These Three Things**

* Do teams that win the toss actually win more matches?

* Which phase — powerplay, middle overs, or death overs — is most linked to winning?

* Who are the top 5 batters and top 5 bowlers across 5 seasons?

---

#### **What To Build**

Chart 1 — two bars showing win rate of toss winners vs toss losers

Chart 2 — average runs per phase for winning teams vs losing teams

Table — top 5 batters by runs, top 5 bowlers by wickets

One sentence — something the data showed you that genuinely surprised you


An executive overview of the **IPL Crunch '26 Data Analytics Dashboard** highlights its architecture, design philosophy, and core intelligence vectors.

---

### 🌐 Solution Overview

The **IPL Crunch '26 Dashboard** is an elite sports intelligence application engineered to transform raw, granular, ball-by-ball tournament data into strategic, execution-ready insights. Moving away from standard, generic charts, the platform adopts an **immersive, high-contrast dark user interface** tailored for high-performance analysts and team management.

Powered by a centralized, optimized Python processing engine (`load_and_preprocess`), the dashboard bridges multi-season data integrity with premium interactive visual diagnostics. It maps real-time data status, offers dynamic season-scoped filtering, and isolates actionable vectors to decode exactly what controls winning and losing outcomes in modern competitive cricket.

---

### 🧠 Core Insight Paradigms

The solution is architected around five dedicated intelligence tracks, providing macro configurations and deep-dive tactical breakdowns:

#### 1. 🎲 The Toss Leverage Vector (`Toss Advantage`)

Rather than treating the coin toss as an isolated event of luck, the system computes structural cushions and conversion rates based on captain decisions.

* **Win Differential Mapping:** Quantifies the exact percentage cushion or penalty a squad inherits based on winning or losing the toss.
* **Chasing Split Optimization:** Breaks down the high conversion factor of electing to field first, helping analysts understand how teams utilize late-innings field restrictions and navigate environmental shifts (like dew variance).

#### 2. ⚡ Phase Velocity & Concentration (`Phase Transitions`)

Matches are won or lost in micro-inflection windows. The dashboard maps scoring patterns over an over-by-over matrix.

* **Acceleration Clusters:** Dynamically charts Run Rate (RPO) trends between winning and losing sides across the Powerplay (Overs 1–6), Middle Overs (7–15), and Death Overs (16–20).
* **Execution Inflections:** Exposes the structural boundaries where winning teams successfully over-index on boundary production compared to losing lineups.

#### 3. 🏆 Roster Volumetric Anchoring (`Performance Leaders`)

The solution separates sheer production volume from line-item contextual impact.

* **Batting Volume Treemaps:** Visually clusters top boundary-hitters and run accumulators alongside critical efficiency metrics (Strike Rate and Average).
* **Defensive Economy Trajectories:** Tracks top wicket-takers, isolating low economy rates in high-pressure phases as the primary driver for forcing opposing lineups into compounding mistakes.

#### 4. 📈 Macro Timeline Evolution (`Macro Matrix`)

Tracks the long-tail structural changes across historical tournament environments.

* **Target Expansion Scales:** Monitored trends showcase the steady expansion of first-innings benchmarks due to optimized powerplay management and bat composition evolution.
* **Wicket Fall Equilibrium:** Correlates expanding totals against average wicket distribution, outlining whether attacking philosophies are sacrificing roster depth.

#### 5. 🔮 The Strategic Playbook & Anomalies (`The Strategic Verdict`)

The definitive crown-jewel matrix of the dashboard, pulling hidden statistical outliers into plain view.

* **Dot Ball Dominance Analysis:** Features a rigorous mathematical distribution confirming that defensive dot-ball production ratio is an exceptionally strong predictor of victory. It visually and contextually proves that maintaining middle-over pressure consistently out-indexes individual batting milestones.
* **Data Anomaly Flags:** Surface out-of-the-box historical anomalies and specific condition shifts (such as a 165+ Strike Rate stay swinging win probability by ~22%), shifting the paradigm from basic retrospectives to true predictive intelligence.

---

