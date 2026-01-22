# Graph Analytics of the USA Road Network using Neo4j

## 📌 Project Overview
This project presents a graph-based analysis of the United States road network using **Neo4j** and **Graph Data Science (GDS)** techniques. Intersections are modeled as nodes and roads as relationships, enabling the application of graph algorithms such as shortest path, degree analysis, and betweenness centrality to extract meaningful insights from large-scale transportation data.

The project was completed as part of the **Big Data Analytics** course at the **Adventist University of Central Africa (AUCA)**.

---

## 🎓 Course Information
- **Course Name:** Big Data Analytics  
- **Course Code:** MSDA9215  
- **Lecturer:** Temitope Oguntade  
- **Institution:** Adventist University of Central Africa (AUCA)

---

## 👥 Group Members
| Name | Registration Number |
|-----|---------------------|
| RUSINGIZWA Jean Pierre | 101086 |
| AKIRI Olivier | 101062 |
| UWASE Carine | 101030 |

---

## 🗂️ Dataset Description
The dataset represents the continental United States road network and includes:
- **87,575 intersections**
- **121,961 roads**

Intersections are stored as `Intersection` nodes, and roads are stored as `ROAD` relationships.  
Euclidean distance between intersections is used as the edge weight.

---

## 🛠️ Tools & Technologies
- **Neo4j Desktop**
- **Cypher Query Language**
- **Neo4j Graph Data Science (GDS) Library**
- **APOC Procedures**
- **Python**
- **Plotly**
- **Jupyter Notebook**

---

## 📊 Tasks Performed
1. Data import and graph modeling in Neo4j  
2. Shortest path computation using Dijkstra’s algorithm  
3. Degree analysis of intersections  
4. Betweenness centrality analysis using GDS  
5. Interactive dashboards with Plotly  
6. Degree distribution analysis  
7. Identification of top connected intersections  
8. Connectivity categorization (Low, Medium, High)  
9. Visualization and interpretation of network structure  

---

## 📈 Key Insights
- The road network is **sparse**, with most intersections having low degree.
- A small number of intersections act as **highly connected hubs**.
- Betweenness centrality highlights **critical junctions** that play an important role in network connectivity.
- Graph analytics provides an efficient way to analyze large transportation networks.

---

