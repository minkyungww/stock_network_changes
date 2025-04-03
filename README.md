# Analyzing the Network Structure and Dynamic Changes of Major Financial Market Sectors Before and After Economic Crises

This project investigates how major economic crises impact the structure and dynamics of the financial market using network analysis techniques. The study focuses on Korea's KOSPI stock market across three major crises: the 1997 IMF financial crisis, the 2008 subprime mortgage crisis, and the 2020 COVID-19 pandemic.

## 📌 Objectives

- Analyze structural shifts in the Korean financial market before and after economic crises.
- Apply network theory techniques (MST, centrality, community detection).
- Develop portfolio strategies that adapt to changing market conditions.

## 📊 Methodology

- **Data Source**: Daily closing prices of top 100 KOSPI-listed companies.
- **Graph Construction**:
  - Correlation → Distance transformation
  - Network built using significant edges (top 10%)
- **Analytical Methods**:
  - **Minimum Spanning Tree (MST)**
  - **Centrality Analysis** (Degree, Closeness, Betweenness, Eigenvector)
  - **Community Detection** (Louvain method)

## 💡 Key Findings

- Centrality generally increases during crises, indicating stronger market-wide connectivity.
- The number of distinct communities decreases, reflecting a more unified market response.
- Dominant industries shift:
  - Pre-IMF: Financial & securities firms
  - Post-IMF & Subprime: Raw materials & heavy industries
  - Post-COVID: Tech, e-commerce, and domestic market-oriented firms

## 📈 Investment Strategy

- Defined new sectors based on degree centrality:
  - **Hub & Spoke** (high centrality)
  - **Chain Link** (medium centrality)
  - **Fringe Player** (low centrality)
- Constructed efficient frontiers before, during, and after the IMF crisis.
- Portfolio optimization showed how rebalancing can minimize risk during downturns.

## 🛠 Tools & Technologies

- Python
- NetworkX
- Pandas, NumPy
- Matplotlib, Seaborn


## 🧑‍💻 Authors

- Jaewoong Jeong (jaywoong.jeong@kaist.ac.kr)  
- Hyeongmin Park (mike980409@kaist.ac.kr)  
- Juchan Lee (jclee0109@kaist.ac.kr)  
- Minkyung Choi (minkyungww@kaist.ac.kr)  
(Korea Advanced Institute of Science and Technology)
