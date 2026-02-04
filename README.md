Team Performance and Squad Structure

Dataset construction and applied analysis of Premier League squad structure and team performance using Excel and Stata.

The objective of this project is to construct a team-level dataset for English Premier League clubs and examine how squad structure and composition are associated with on-field performance. The emphasis of the project is on data preparation and variable construction, with analysis used to demonstrate how the dataset can be applied in practice.

Dataset Overview

The dataset covers Premier League club-seasons from 2013/14 to 2017/18, resulting in an unbalanced panel of 100 club-season observations.

Underlying data were sourced from Transfermarkt, which provides player-level market values, nationality information, and squad characteristics.

Team performance is measured using points per match, allowing comparability across seasons.

Dataset Construction (Core Contribution)

The main work in this project involved transforming player-level squad data into a structured, team-level analytical dataset.

Key steps included:

Collected player-level squad data for Premier League clubs across five seasons

Aggregated player-level information to a club–season level, defining the unit of observation

Constructed points per match as a standardised performance measure

Calculated market value inequality within squads using the Gini coefficient of individual player market values

Measured nationality concentration using the Herfindahl–Hirschman Index based on players nationalities

Defined squad composition variables including squad size, average squad age, and the share of native players

Computed each club’s share of total league market value to control for relative financial strength

Checked consistency of variable definitions across seasons and handled missing or inconsistent values during preparation

Dataset construction and cleaning were primarily carried out in Excel, with the final analytical dataset exported for analysis.

Data Preparation

Data preparation focused on ensuring consistency and comparability across clubs and seasons. This included:

standardising variable definitions across seasons

validating constructed inequality and concentration indices

checking for outliers and implausible values

ensuring all variables fell within expected ranges

The Excel file included in this repository contains a reduced version of the dataset used for analysis, focusing on the key variable construction and aggregation steps.

Analysis

Analysis was conducted in Stata using a fixed-effects regression framework.

Club fixed effects control for time-invariant differences between clubs

Season fixed effects control for league-wide seasonal influences

The analysis exploits within-club changes in squad structure over time

The analysis examines associations between squad structure and performance rather than making causal claims.

A summary of the analysis and results is provided in the accompanying PDF document.

Key Findings

Relative financial strength (share of total league market value) is strongly associated with team performance

Measures of internal squad inequality and nationality composition do not show robust independent associations once financial controls are included

Squad size and average squad age are negatively associated with points per match

These results illustrate how the constructed dataset can be used to evaluate structural hypotheses in a professional sports context.

Limitations

Market values from Transfermarkt are estimates rather than observed transaction prices

The sample is limited to five Premier League seasons

Results should be interpreted as associations, not causal effects
