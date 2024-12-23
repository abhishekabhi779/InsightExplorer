[Report.pdf](https://github.com/user-attachments/files/18225490/Report.pdf)




# Research Insight Explorer

**Author:** Abhishek Sattu  

**Advisor:** Prof. Scott Spetka  

## Introduction
The Research Insight Explorer is a web-based application designed to organize, analyze, and visualize academic research data. It leverages graph database technology to uncover relationships among authors, papers, and topics, providing an interactive platform for researchers and academics.

## Features
- **Advanced Search:** Filter research papers by authors, topics, or publication year.
- **Interactive Visualizations:** Explore connections between research entities using dynamic graph visualizations.
- **Data Integration:** Ingest data from OpenAlex into a Neo4j graph database for efficient querying.
- **Modern Design:** User-friendly interface with responsive design.

## Technology Stack
- **Backend:** Flask (Python-based framework)
- **Database:** Neo4j (Graph database)
- **Frontend:** HTML, CSS, Bootstrap, Jinja2
- **Visualization Tools:** PyVis, NetworkX

## System Architecture
1. **Database Layer:** Neo4j for managing nodes and relationships.
2. **Application Logic Layer:** Flask-based backend to handle queries and serve data.
3. **Presentation Layer:** Dynamic web interface using Jinja2 and Bootstrap.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/insightexplorer.git
