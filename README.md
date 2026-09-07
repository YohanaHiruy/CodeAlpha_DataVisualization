# Wine Chemistry Data Visualization

I Visualized chemical properties of 178 wine samples across 3 grape varieties to see 
whether chemistry alone can distinguish between them.

## Key Findings
- Flavanoids show the cleanest separation between the three wine classes, with very 
  little overlap — making it the strongest single indicator of grape variety.
- Color intensity and Alcohol also show meaningful separation between classes, 
  though with more overlap than Flavanoids.
- The correlation heatmap reveals that phenol-related compounds (Total phenols, 
  Flavanoids, OD280/OD315) are strongly interrelated.
- The pairplot confirms that combining Flavanoids, Color intensity, and Alcohol 
  produces visually distinct clusters for each wine class.

## Tools used
Python, pandas, seaborn, matplotlib

## Limitations
The Dataset is small (178 samples) and pre-processed/clean, so real-world wine data may 
show more noise and overlap between classes.
