# Predicting Early Match Success in League of Legends
<b>Project by:</b> Gabrielle Despaigne
<br>
<b>DSC 259R Final Project

<h2>Introduction</h2>
This project analyzes professional League of Legends match data from the 2022 competitive season to understand how early-game advantages influence match outcomes. Competitive League of Legends is often described as “snowbally,” meaning that early leads can cascade into decisive victories. However, not all early advantages are equal. This project is centered around one core question:

Is early objective control or first blood a stronger indicator of match outcome in professional League of Legends matches?

Understanding this relationship matters for several reasons. From a competitive standpoint, it informs strategic decision-making: should teams prioritize early neutral objectives such as dragons and heralds, or early combat advantages like first blood? From a data science perspective, this dataset provides a structured environment to evaluate how early signals translate into final outcomes, and whether magnitude-based metrics (such as gold difference) provide more predictive power than binary early events alone.

The dataset contains team-level observations from professional matches played during the 2022 season. After filtering to team-level rows (two rows per match: one per team), the working dataset contains 24,830 rows. Each row represents one team’s perspective in a single match.

The columns most relevant to this project include:

<b>- result</b> — Binary indicator of match outcome (1 = win, 0 = loss). This is the response variable for both hypothesis testing and predictive modeling.

<b>- early_objective_control</b> — Engineered binary feature indicating whether a team secured at least one early neutral objective (first dragon, first herald, or first tower).

<b>- firstblood</b> — Binary indicator of whether a team secured the first kill of the match.

<b>- golddiffat10</b> — Gold difference between the team and their opponent at 10 minutes. This captures the magnitude of early economic advantage.

<b>- killsat10</b> — Number of kills secured by the team at 10 minutes.

<b>- side</b> — Categorical variable indicating whether the team played on the blue or red side.

By combining statistical inference and predictive modeling, this project evaluates whether early-game events and advantages meaningfully shape match outcomes and whether continuous measures of early advantage improve predictive performance beyond simple binary indicators.

<h2>Data Cleaning and Exploratory Data Analysis</h2>

<h2>Assessment of Missingness</h2>

<h2>Hypothesis Testing</h2>

<h2>Framing a Prediction Problem</h2>

<h2>Baseline Model</h2>

<h2>Final Model</h2>

<h2>Fairness Analysis</h2>
