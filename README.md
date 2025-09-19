**Overview**

This project investigates how background music (silence, instrumental, lyrical) and text formatting (bulleted vs. comma-separated lists) affect short-term memory recall and comprehension.

Our goal was to determine whether music or text structure has a measurable effect on participants’ ability to accurately recall words/phrases and the time taken to recall them.

**Methodology**
Step 1: Research & Literature Review

- Reviewed prior studies on music’s effect on cognition and text formatting’s effect on memory recall.

- Formulated hypotheses:

  - H0: No effect of music or text formatting.

  - H1: Silence improves recall over music; bulleted lists improve recall over paragraphs.

  - H2: Interaction effect exists (music × format).

Step 2: Experiment Design

- Participants: 16 university students, fluent in English, no hearing impairments.

- Conditions:
  - Silence / Instrumental / Lyrical × Bulleted / Comma-Separated.
  - Each participant completed 6 randomized trials.

- Apparatus: headphones, stopwatch, recall sheets, controlled word lists.

Step 3: Data Collection

- Measured:

 - Recall accuracy (score out of 10).

 - Recall time (seconds).

- Ensured consistency: same two songs, fixed volume, structured trial design.

Step 4: Data Analysis

- Tests performed in R:

  - Shapiro–Wilk test (normality check).

  - Levene’s test (variance homogeneity).

  - Two-way ANOVA (effects of music, format, and interaction).

  - Eta-squared effect size analysis.

Step 5: Results & Visualization

- Main effects of music and format were not statistically significant.

- Interaction effect (p = 0.0417, η² = 0.07) was significant:

- Instrumental music improved recall for comma-separated lists.

- Lyrical music improved recall for bulleted lists.

- Silence yielded consistent performance across both formats.

Step 6: Discussion & Conclusion

- Neither factor alone significantly influenced recall.

- The combination of music type and format did affect performance.

- Suggests distraction levels and visual clarity play roles in memory tasks.

- Future work: expand sample size, explore more music genres, assess individual study habits.
