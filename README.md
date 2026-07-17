### Hi there 👋 My name is Vladislav Fedorov

I'm a statistician with a broad focus on applied data analysis, statistical modeling, and interactive tools, spanning domains from clinical trial design and drug safety analysis to esports analytics. I hold a Master of Science in Statistics from the University of Illinois Urbana-Champaign (GPA 3.90), along with a Bachelor of Liberal Arts and Sciences in Statistics (GPA 3.77), with a minor in Mathematics, from the same university.

I work primarily in R and Python, with SAS as well, and have client-facing statistical consulting experience translating technical findings into stakeholder-ready recommendations.

Outside of my statistics work, I build games in Unity and C#, from solo long-term projects to 48-72 hour game jam entries. I enjoy building end-to-end projects generally, from data preparation and modeling to interactive tools and games.

You can find my statistics and data science projects below, followed by my game development work.

# 📊 Statistics/Data Science Projects

### Clinical Trial Power Calculator

- Built a two-arm clinical trial sample size and power calculator in Python (Streamlit), covering continuous, binary, and time-to-event endpoints with closed-form formulas (noncentral t, arcsine, Schoenfeld) alongside simulation-based power that fits the actual regression model (ANCOVA, logistic regression, Cox PH) to synthetic trial data.
- Validated every closed-form formula against independent benchmarks, surfaced a real power gap between closed-form targets and Wald-test-based regression analyses across two endpoint types, and anchored a worked example to the HR of 5.03 finding from the CDISC safety analysis project.

[Repo](https://github.com/ValDevelopment/clinical-trial-power-calculator)

[Live App](https://clinical-trial-power-calculator.streamlit.app)

### Clinical Trial Safety Analysis

- Built a full CDISC SDTM/ADaM analysis pipeline in R on a public 254-patient Alzheimer's trial dataset, covering baseline demographics, adverse event summarization, and time-to-event survival analysis.
- Modeled time-to-adverse-event with Kaplan-Meier curves and a Cox proportional hazards model, uncovering a dose-response safety signal (HR of 4.15 and 5.03 vs. placebo) confirmed by an age-adjusted sensitivity analysis.
  
[Repo](https://github.com/ValDevelopment/CDISC-ADaM-Survival-Analysis)

[Report](https://github.com/ValDevelopment/CDISC-ADaM-Survival-Analysis/blob/main/cdisc_report.pdf)

### FAERS Disproportionality Analysis: Semaglutide

- Ran a post-market drug safety signal detection analysis on FDA FAERS Q4 2025 data for semaglutide (Ozempic, Wegovy, Rybelsus), applying PRR, ROR, and chi-square disproportionality methods with Haldane-Anscombe correction across 3,279 primary-suspect case reports.
- Built the pipeline independently in Python and SAS, validated both implementations to match exactly, and curated the flagged signals against MedDRA coding noise and published GLP-1 safety literature.
  
[Repo](https://github.com/ValDevelopment/FAERS-signal-detection)

### Counter-Strike Team Analysis Tool

- Analyzed CS:GO match and team-level data to study economy-driven decision-making across rounds.
- Merged and transformed match datasets to track transitions between eco, force, and full-buy rounds, and visualized their relationship to round outcomes using interactive plots.

[Repo](https://github.com/ValDevelopment/CS-GO-Team-Economy)

[Live App](https://counter-strike-analytics.streamlit.app/)


### Indie Publisher Recommendation Tool

- Developed a content-based recommender system to help indie developers identify potential publishers based on historical catalog similarity.
- Matched game concepts—defined by Steam tags and target price point—to publishers with comparable releases, and surfaces concrete examples to support discovery and outreach.

[Repo](https://github.com/ValDevelopment/Game-Sales-Project)

[Live App](https://indie-publisher-search.streamlit.app/)


### Text-Based Geographic Region Classification Tool

- Built text-based classification models to predict the geographic region of tweets using textual features. I focused on TF-IDF representations, class imbalance mitigation, and random forest modeling to improve predictive performance.
- The broader project also explored logistic regression baselines and BiLSTM models for sequential text patterns, implemented by other team members.

[Repo](https://github.com/Rsrirajan/NLP-DisasterTweets)  

[Report](https://github.com/ValDevelopment/TweetLocations/blob/main/Predicting_Tweet_Locations_Report.pdf)


# 🎮 Gamedev Projects
### [Play my games!](https://valdevelopment.itch.io/)

<!--
## The Last Spellwright
### A personal long-term project: a 2D roguelike deck-builder built around spell composition. Cards modify a spell state by adding elemental components rather than resolving fixed effects.

Core mechanics:
- Elemental cards contribute to a spell state that is resolved on cast
  - Spells can either resolve as the sum of their components, combining elemental effects with optional Shape and Style modifiers, or as specific spells with strict composition requirements and higher payoff
- Combat emphasizes knowledge and mana efficiency
- Elemental levels scale dynamically with deck composition and provide passive power increases
- Increasing deck size trades spellcasting consistency for broader access to power

[Playable Demo](https://valdevelopment.itch.io/the-last-spellwright)  
-->
## Game Jams
 
### Dino's Nightmare
#### Created in 72 hours for [Mini Jam 120](https://itch.io/jam/mini-jam-120-hell)
#### Roles: Gameplay Programmer, Level Designer

#### Out of 56 submissions, our game placed 1st in Presentation and 3rd in Overall rankings.

[Repo](https://github.com/Lockd/Hell-dodgeball)  
[Link](https://lockd.itch.io/dinos-nightmare) 


### Windows Defense 
#### Created in 72 hours for [Mini Jam 121](https://itch.io/jam/mini-jam-121-reflection)
#### Role: Gameplay, UI Programmer

#### Out of 120 submissions, our game placed 7th in Enjoyment and 21st in Overall rankings.

[Repo](https://github.com/Lockd/windows-td)  
[Link](https://lockd.itch.io/windows-defense)  


### Gentle (g)host
#### Created in 48 hours for [GMTK Game Jam 2023](https://itch.io/jam/gmtk-2023)
#### Role: UI Programmer

#### Out of 6769 submissions, our game placed 72nd in Presentation and 198th in Overall rankings.

[Repo](https://github.com/Lockd/gmtk2023/tree/main)  
[Link](https://ldrg.itch.io/gentleghost)  
