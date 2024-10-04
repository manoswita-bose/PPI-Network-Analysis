# PPI-Network-Analysis
Unraveling the Network Landscape: A Comparative Analytical Approach to Investigate Protein–Protein Interaction Networks in Normal v/s Tumor Cells

## Overview
This study was done primarily for my Undergrad Major Project. It is focused on analyzing and comparing Protein-Protein Interaction (PPI) networks between normal and tumor cells. The study employs network analysis techniques to understand the structural differences in protein interactions across different types of human cells, providing insights into cancer development and progression.

## Dataset Information
My study was centered on analyzing PPI networks from 5 different tissue types:
- Bone
- Breast
- Colon
- Kidney
- Liver

Each tissue type included 2 datasets:
- Normal cell PPI network data
- Tumor cell PPI network data

## Tools and Technologies
- **Programming Language**: Python (NetworkX, Matplotlib, Seaborn)
- **Visualization**: Gephi
- **Data Formats**: TXT, CSV files containing PPI data for bone, breast, colon, kidney, and liver
- **Platform**: Google Colaboratory

## Methodology
**Data Processing Pipeline** - The study involved the following steps:
- **Data Collection**: PPI data was obtained from reliable public sources.
- **Data Preprocessing**: The data was cleaned, standardized, and divided based on normal and tumor cell data.
- **Network Analysis**: Metrics such as node degree, betweenness centrality, clustering coefficient, and network density were computed.
- **Visualization**: Matplotlib, Seaborn, and Gephi were used to generate visual representations to highlight structural differences in the networks.
- **Interpretation**: Results were analyzed to understand differences in network topology between normal and tumor cells.

**Analysis Metrics** - The study examined several network parameters that included:
- Number of nodes and edges
- Average degree
- Network diameter
- Graph density
- Modularity
- Connected components
- Average clustering coefficient
- Average path length

## Key Findings
**Size Differences**:
- Cancer networks generally showed increased size compared to normal networks
- Higher number of nodes and edges in tumor cell networks

**Structural Variations**:
- Different connectivity patterns between normal and cancer networks
- Variations in node degree distribution
- Changes in network density and clustering

**Topological Features**:
- Cancer networks showed more fragmented or disorganized structures
- Normal networks exhibited more structured or modular organization

## Technical Requirements for Usage
To reproduce this analysis, you will need:
- Python 3.x
- NetworkX
- Matplotlib
- Seaborn
- Gephi (for visualization)
    
## Authors
- [@manoswita-bose](https://github.com/manoswita-bose)

## Support
Feel free to reach out to [me](manoswita.bose@gmail.com) for questions or support.
