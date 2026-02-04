This project focuses on constructing a team-level dataset for English Premier League clubs and using it to examine how squad structure relates to on-field performance. The emphasis is on data preparation and variable construction, with analysis included to demonstrate how the dataset can be applied.

The dataset covers Premier League club-seasons from 2013/14 to 2017/18 and consists of 100 club-season observations. Player-level data were sourced from Transfermarkt and aggregated to the club–season level. Team performance is measured using points per match to allow comparison across seasons.

During dataset preparation, several key variables were constructed. Internal squad inequality was measured using the Gini coefficient of player market values, nationality concentration was captured using the Herfindahl–Hirschman Index, and squad composition measures included squad size, average age, and the share of native players. Each club’s share of total league market value was calculated to account for differences in financial strength. Dataset construction and cleaning were carried out primarily in Excel.

The prepared dataset was analysed in Stata using fixed-effects regression, controlling for club and season effects. The analysis examines associations between squad characteristics and performance rather than making causal claims. A summary of the analysis is provided in the accompanying PDF.

Results indicate that relative financial strength is strongly associated with performance, while measures of squad inequality and nationality composition do not show robust independent relationships once financial controls are included. Squad size and average age are negatively associated with points per match.

The Excel file included in this repository is the primary working file used for dataset construction and aggregation. Market values are estimates, and results should be interpreted as associations rather than causal effects.
