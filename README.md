# KEGG Analysis of Enzyme 5.4.2.2 (Alpha-D-Glucose 1,6-Biphosphate)

This project performs a KEGG (Kyoto Encyclopedia of Genes and Genomes) pathway analysis for **Enzyme 5.4.2.2**, also known as **alpha-D-glucose 1,6-biphosphate**. The goal of this analysis is to explore the metabolic pathways in which this enzyme participates, utilizing the KEGG database for pathway enrichment and network analysis.

## Technologies Used
- **Python 3.x**
- **KEGG API**: For retrieving pathway data and enzyme information.
- **NetworkX**: For creating and visualizing networks.
- **Matplotlib**: For visualizing pathway and gene networks.
- **BioPython**: For parsing KEGG data.

## Project Overview
This project focuses on the analysis of the enzyme **alpha-D-glucose 1,6-biphosphate**, which is involved in glucose metabolism. The project retrieves pathway information from the KEGG database, maps the enzyme to relevant metabolic pathways, and visualizes its interactions with associated genes and pathways.

### Key Features
- Retrieval of enzyme information from KEGG.
- Pathway analysis and visualization using KEGG's data.
- Network visualization of enzyme-gene and enzyme-pathway interactions.
- Output of significant pathways and associated enzyme functions.


## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/KEGG-Analysis-Enzyme-5-4-2-2.git
   cd KEGG-Analysis-Enzyme-5-4-2-2
   ```

2. Install the required Python libraries:
   ```bash
   pip install biopython networkx matplotlib
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "KEGG Analysis for Genes and Pathways Enzyme - EC 5 4 2 2.ipynb"
   ```

## Outputs
The outputs of the analysis include visualizations of the enzyme's interactions with genes and pathways. These outputs are stored in the `Outputs` folder.
<p align="center">
   <a>
   <img width="800px" height="800px" src="https://imgur.com/owvz9Vn.jpg"/>
   </a>
</p>

<div align="center">
   <a href="https://imgur.com/H1rzwIS">
</div>

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
