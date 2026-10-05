# Friendship Network Analysis Using Graph Theory

## About the Project

This project analyzes a friendship network using graph theory and network analysis techniques.

Each student is represented as a node, and a friendship connection between two students is represented as an edge. The project explores the structure of the network and identifies important nodes and communities.

## Objectives

- Represent friendship relationships as a graph
- Analyze the structure of the friendship network
- Identify important and highly connected nodes
- Detect communities within the network
- Apply PageRank to analyze node importance
- Visualize the friendship network

## Technologies Used

- Python
- NetworkX
- Pandas
- Matplotlib
- python-louvain

## Analysis Performed

The notebook includes:

- Graph creation and network visualization
- Degree and network analysis
- Centrality analysis
- Community detection using the Louvain method
- PageRank analysis
- Community density analysis

## Dataset

The dataset contains friendship relationships represented using anonymized student identifiers such as `Student_01`, `Student_02`, etc.

The original personal names have been replaced with anonymized identifiers to protect privacy.

## Files

- `Analysis.ipynb` — Jupyter Notebook containing the complete analysis
- `friendship_network.csv` — Anonymized friendship network dataset

## How to Run

1. Download or clone this repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Install the required libraries:

```bash
pip install pandas networkx matplotlib python-louvain
