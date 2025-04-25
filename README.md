# social_media_data_analysis
Master Course

🚌 Metro–Bus Network Optimization for Ho Chi Minh City
This project presents a data-driven optimization model for restructuring Ho Chi Minh City's public bus network in alignment with the future Metro system, using spatial data analysis, graph theory, and Python-based libraries.

📘 Project Overview
Course: Phân Tích Dữ Liệu Mạng Xã Hội (Social Network Data Analysis)
Institution: Trường Công nghệ và Thiết kế – Đại học UEH
Group: Nhóm 3 – Lớp Cao học Công nghệ Thiết kế Thông tin K33.2
Instructor: TS. Nguyễn Thành Huy
Date: January 2025

🚀 Objectives
Evaluate the current bus network's limitations in connectivity and overlap with the Metro system.

Integrate and optimize a feeder bus system (Metro–Feeder Model) that enhances access to Metro stations.

Apply graph-theoretical metrics (Degree Centrality & PageRank) to identify and preserve critical nodes.

Visualize network changes and propose a more sustainable, user-friendly public transport framework for HCMC.

📌 Key Features
✅ Data Sources
Metro Station Data: Manually geocoded using city planning maps and Google Maps API.

Bus Stops: Extracted from OpenStreetMap using osmnx.

🧠 Techniques Used
Graph Modeling: Using NetworkX and OSMnx to represent and analyze transportation networks.

Ball Tree Algorithm: Used to find and remove overlapping stations within 1km of metro stations.

Clustering: Assign each bus station to its nearest Metro stop and classify it as Main or Sub feeder.

Centrality Metrics: Used Degree Centrality and PageRank to refine the network by removing low-impact nodes.

📊 Results
Reduced the number of bus stops from 4,754 to 1,993 (58% reduction).

Created a structured feeder system: Metro → Main Feeder → Sub Feeder.

Ensured better connectivity and less redundancy in the overall transport network.

🛠 Tools & Libraries
Python

Pandas & NumPy

NetworkX

OSMnx

GeoPandas

Scikit-learn

QGIS (for map visualization)
