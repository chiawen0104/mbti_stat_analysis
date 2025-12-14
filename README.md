# mbti_stat_analysis

## Statistical Independence and Correlation Analysis among MBTI Personality Dimensions


This project investigates the probabilistic relationships among the four fundamental dimensions of the Myers-Briggs Type Indicator (MBTI): Extraversion–Introversion (E), Sensing–Intuition (N), Thinking–Feeling (F), and Judging–Perceiving (P). Although the MBTI framework treats its four dimensions as distinct personality axes, previous empirical findings suggest that they may not be statistically independent in practice. Using a dataset containing demographic variables (age, gender, and education level) and quantitative scores for each of the four dimensions (ranging from 1 to 10), this study aims to examine whether the MBTI traits are statistically independent or correlated in real human data.

Each MBTI dimension is modeled as a continuous random variable representing an individual’s psychological preference strength. The analysis first estimates marginal distributions and computes pairwise covariance and Pearson correlation coefficients to quantify linear dependencies among the four dimensions. To further explore potential non-linear relationships, mutual information and partial correlation analyses are conducted under both unconditional and stratified conditions (e.g., within specific gender or age groups). Visualization techniques—including heatmaps, scatter plots, and covariance matrices—are employed to illustrate the joint patterns and interdependence across dimensions.

Unlike many studies that focus on predicting a person’s MBTI type or classifying text, this project takes a structural approach to analyze the relationships among the four MBTI dimensions themselves. By modeling each dimension as a continuous random variable, we can uncover how these traits interact rather than treating them as isolated categories. This probabilistic analysis helps reveal whether certain traits tend to co-occur, oppose each other, or remain largely independent. Understanding these structural patterns not only deepens our statistical view of personality but also provides insight for improving psychological assessments, designing personality-based recommendation systems, and refining future personality models.


## Used Packages

- matplotlib
- seaborn
- sklearn
- pingouin
- scipy

