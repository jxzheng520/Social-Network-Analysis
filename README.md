# Social-Network-Analysis
Social network analysis techniques to explore romantic crush relationships among Harry Potter characters. The analysis demonstrates a complete network analytics workflow: data cleaning, transformation, visualization, and analytical interpretation using graph theory metrics.

# Skills
- Network Analysis: igraph, Social Network Analysis, Graph Theory
- Data Transformation: Data Cleaning, Data Modeling
- Data Visualization: threejs, Interactive 3D Visualization, R Markdown
- Analytics: Centrality Analysis (Degree, Betweenness), Reciprocity Analysis, Network Resilience

# Methodology
- Data Cleaning: Removed loops, verified data integrity, validated there were no null values
- Network Transformation: Converted raw relationship data into a directed graph structure
- Network Visualization: Generated basic network plots for initial exploration
- Interactive Visualization: Created 3D, rotatable scatter plot of the crush network
- Centrality Analysis: Calculated degree centrality to identify the most sought-after characters
- Reciprocity Analysis: Identified which relationships were mutually reciprocated vs. one-sided

# Key Findings
- Network Size: 18 nodes (characters) connected by 18 directed edges (crush relationships)
- Network Cleanliness: Removed 1 loop edge; zero missing values in the cleaned dataset
- Centrality Analysis: Identified characters with highest degree centrality (most "crushed on")
- Reciprocity: Determined which crushes were mutual vs. unreciprocated
- Network Asymmetry: Analysis revealed significant imbalance in romantic interest, with a small number of characters receiving the majority of attention
