# COVID-19 and Broadcaster Dataset Analysis

This project analyzes two distinct datasets using a variety of data structures and algorithms (DSA):
1. The COVID-19 global pandemic dataset - analyzing case statistics across countries and regions
2. A Broadcaster dataset - optimizing telecommunication network establishment

## Table of Contents
- [Project Overview](#project-overview)
- [COVID-19 Dataset Analysis](#covid-19-dataset-analysis)
  - [Features](#features)
  - [Data Structures Used](#data-structures-used)
  - [Algorithms Implemented](#algorithms-implemented)
- [Broadcaster Dataset Analysis](#broadcaster-dataset-analysis)
  - [Features](#features-1)
  - [Algorithms Implemented](#algorithms-implemented-1)
- [Installation and Usage](#installation-and-usage)
- [Project Structure](#project-structure)
- [Contributors](#contributors)

## Project Overview

This project applies various data structures and algorithms to analyze real-world datasets:
- For the COVID-19 dataset: Extract insights about pandemic spread, identify trends, and support decision-making processes
- For the Broadcaster dataset: Optimize telecommunication network design for cost and coverage efficiency

## COVID-19 Dataset Analysis

### Features

1. **Data Visualization and Analysis**:
   - View information about all countries' COVID-19 cases
   - Filter countries by specific criteria (name, death threshold)
   - Delete countries with deaths below a threshold
   - Analyze active cases to guide vaccination manufacturing requirements

2. **Comparative Analysis**:
   - Compare two countries using BST node distance metrics
   - Compare statistics between two geographic regions
   - Identify pandemic severity using active case prioritization

3. **Emergency Assessment**:
   - Check countries with emergency or normal pandemic situations using a double-ended priority queue

4. **Advanced Data Structures Implementation**:
   - Create and display AVL trees for recovered cases in specific regions
   - Build max heaps for active cases in the Americas region
   - Sort confirmed cases across all countries
   - Search for data using hashing techniques

### Data Structures Used

- **Linked Lists**: Used to store the primary dataset
- **Binary Search Trees (BST)**: For hierarchical data organization
- **AVL Trees**: Self-balancing BST for efficient operations
- **Max Heap**: For priority-based data management
- **Double-Ended Priority Queue**: For emergency/normal situation assessment
- **Stacks**: For regional data analysis
- **Hash Tables**: For efficient data retrieval

### Algorithms Implemented

- **Insertion Sort**: For sorting confirmed cases
- **Binary Search**: For efficient data retrieval
- **Level-Order Traversal**: For visualizing tree data
- **In-Order Traversal**: For sorted display of tree nodes

## Broadcaster Dataset Analysis

This component analyzes telecommunications data to optimize network deployment.

### Features

1. **Network Delay Analysis**:
   - Calculate minimum time for a signal to reach all broadcasters from a designated source
   - Identify optimal signal pathways in the network

2. **Cost Optimization**:
   - Determine minimum cost paths from source to each broadcaster
   - Maximize household coverage while minimizing expenses

3. **Tower Placement Optimization**:
   - Identify optimal locations for broadcast towers to minimize costs
   - Maximize household coverage with minimum infrastructure

4. **Time Efficiency Analysis**:
   - Determine minimum time required to traverse all broadcasters
   - Identify the edges with minimum transmission time

### Algorithms Implemented

- **Dijkstra's Algorithm**: For finding shortest paths between nodes
  - Optimized for both time and cost metrics
  - Used to calculate minimum network delay and cost-effective paths

- **Prim's Algorithm**: For minimum spanning tree construction
  - Identifies optimal tower placement to minimize overall network cost
  - Determines the most time-efficient network configuration

## Installation and Usage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/covid19-broadcaster-data-analysis.git
   ```

2. Compile the program:
   ```
   g++ -o covid_broadcaster CoronaAndBroadcasterDataset.cpp
   ```

3. Run the executable:
   ```
   ./covid_broadcaster
   ```

4. Follow the menu options to explore different analyses

## Project Structure

```
├── CoronaAndBroadcasterDataset.cpp    # Main source code
├── country_wise_latest.csv            # COVID-19 dataset
├── broadcaster.csv                    # Broadcaster network dataset
└── README.md                          # Project documentation
```

## Contributors

- [Your Name]
- [Team Member 2]
- [Team Member 3]

---

This project was developed as part of the Data Structures and Algorithms Laboratory course.
