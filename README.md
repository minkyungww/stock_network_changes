Analyzing the Network Structure and Dynamic Changes of Major Financial Market Sectors Before and After Economic Crises
This project investigates how major economic crises affect the structural dynamics of financial markets using network analysis. Focusing on the Korean KOSPI stock market, we analyze the periods before and after the 1997 IMF financial crisis, the 2008 subprime mortgage crisis, and the 2020 COVID-19 pandemic.

📌 Objectives
Examine structural changes in the financial market using network analysis.

Analyze how industries gain or lose centrality during times of crisis.

Apply methods like Minimum Spanning Tree (MST), centrality measures, and community detection.

Develop sector-based investment strategies resilient to economic shocks.

📊 Methodology
Data: Daily closing prices of KOSPI-listed stocks across different crisis periods.

Graph Construction:

Use correlation matrices to build distance graphs.

Filter edges to retain the most significant relationships.

Analysis Techniques:

Minimum Spanning Tree (MST) to understand core-peripheral relationships.

Centrality Metrics (Degree, Closeness, Betweenness, Eigenvector) to identify influential stocks.

Community Detection via the Louvain method to detect clusters of companies.

💡 Key Findings
During crises, market centrality increases, and communities become fewer, reflecting a unified response to shocks.

The centrality of financial institutions declines, while raw materials, tech, and domestic industries gain importance.

Shifts in centrality during each crisis were unique and aligned with the nature of the crisis (economic, financial, or external).

📈 Investment Strategy Application
Companies were categorized into new sectors: Hub & Spoke, Chain Link, and Fringe Player based on degree centrality.

These sectors were used to construct portfolios and plot efficient frontiers.

Results indicate optimal portfolio adjustments can reduce risk and maintain performance during crises.

🛠 Technologies & Tools
Python (for data processing and graph analysis)

NetworkX

Pandas, NumPy

Matplotlib/Seaborn (for visualization)
