# 🌐 Network-Analysis-Study
## 👥 Authors
- [Pol Monné](https://github.com/pomopa)  
- [Pau Casé](https://github.com/paucase4)

## 📌 Project Overview
This project performs a comparative link analysis on two real-world social network datasets obtained from the [Stanford Network Analysis Project (SNAP)](https://snap.stanford.edu).

The goal is to explore their structural properties, identify influential nodes, detect communities, and compare how different types of social graphs behave.

The study examines:

1. Facebook Social Circles (Ego Networks)
  - Undirected graph of 10 ego-centered friendship networks.
  - Includes anonymized user features and friend-to-friend connections.
2. Twitter Interaction Network – 117th U.S. Congress
  - Directed, weighted graph representing interactions between members of the U.S. House and Senate.
  - Edge weights correspond to volume of interactions.
The analysis highlights differences between ego-centric undirected networks (Facebook) and directed, interaction-based networks (Twitter Congress).

## 📂 Data Overview

### 1. Facebook “Ego” Network
A social network centered around ten individuals (ego nodes):
```0, 107, 348, 414, 686, 698, 1684, 1912, 3437, 3980```

Each ego network contains:
- The ego user
- Their direct friends (alters)
- Connections among those alters

Data was originally collected for research on social circle detection and community inference.

### 2. Twitter U.S. Congress Interactions
A directed, weighted graph of interactions between members of the 117th U.S. Congress.

Key characteristics:
- Graph type: Directed, weighted
- Nodes: 475
- Edges: 13,289
- Edge meaning: Interaction from one member to another (retweets, mentions, etc.)

Used originally for: Studies on influence, spread dynamics, and centrality in political communication networks.

## 📂 Project Structure

| File | Description |
|------|--------------|
| `US_Congress_Notebook.ipynb` | Jupyter Notebook containing the exploration of the Twitter Network. |
| `Link_Analysis_Study.pdf` | Detailed report discussing methodology, results, and conclusions. |
| `requirements.txt` | List of Python packages used. |

## 🧩 Technologies Used
- **Jupyter Notebook** 
- **Python 3**
- **Variety of libraries in the provided requirements.txt**
