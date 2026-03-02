# CS 4990 – Human Perception & Data Visualization
**Project 1 – Graphical Perception (Stevens’ Law)**

Team Members:
- Mira Bhakta [@mirabhakta](https://github.com/mirabhakta)
- Ricky Villanueva [@Psyric](https://github.com/Psyric)
- Youcheng Taing [@Youcheng9](https://github.com/Youcheng9)
- Freeman Yiu [@Coolguy4123](https://github.com/Coolguy4123)

## Project Overview
This project investigates how different visualization encodings affect human perceptual accuracy. We conducted a controlled experiment to compare how accurately participants interpret quantitative data when presented using different visualization types. 

The visualizations were distributed through an online survey sent to friends and classmates. Participants were asked to estimate or compare quantitative values shown in each chart.

A total of 12 responses were collected and used for analysis. For each visualization type, participant answers were compared to the true values in order to calculate accuracy. The results were then grouped by encoding type (position/length vs area/color) to examine differences in perceptual performance.

### Tech stacks
- Python
- Matplotlib
- Numpy

**Research Question:**
Does the type of visual encoding (position, length, area, or color) affect the accuracy of quantitative perception in accordance with Stevens’ Power Law?


### Datasets Used
The following datasets were used in this experiment:
1. Degree Population at HK State Polytechnic
2. EV car sales over multiple years
3. Cancer death rates by age group
4. Annual rainfall data (2015–2026)
5. Olympic medal counts by country
6. Adidas sales over the years

***Note**: All datasets are made up except for Olympic medal counts are recorded by 02/21/2026*

### Visualization Attibutes Used
1. Position: Bar Chart, Line Chart, Horizontal Bar Chart, Grouped Bar Chart
2. Length: Bar Chart, Horizontal Bar Chart, Grouped Bar Chart
3. Area: Area Chart, Bubble Chart
4. Color: Heatmap

## Conclusion
This experiment investigated Stevens’ Power Law by examining how different visual encodings influence perceptual accuracy in quantitative judgment. The results show that participants were significantly more accurate when interpreting charts that relied on position and length compared to those that relied on area and color.

When magnitude was represented through spatial position (bar charts and line charts), participants were able to estimate values more precisely. However, when magnitude was encoded using area (bubble and area charts) or color intensity (heatmaps), accuracy decreased. These findings indicate that perceived magnitude does not scale linearly with actual magnitude for area and color encodings.

**Overall, this experiment demonstrates that visual encoding directly affects perceptual scaling. Position and length produce more accurate quantitative judgments because their perceived magnitude more closely matches actual magnitude, while area and color introduce perceptual distortion consistent with Stevens’ Law.**
