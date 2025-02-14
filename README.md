***Heterogeneous Medical Knowledge Graph from Electronic Health Records***

**Project Overview**

This project involves constructing a heterogeneous medical knowledge graph using Electronic Health Records (EHR). The dataset consists of multiple entity types such as patients, diseases, drugs, and side effects. The goal is to leverage Graph Neural Networks (GNNs) for drug interaction prediction.

**Features**

Medical Knowledge Graph Construction:

1. Integrates structured and unstructured medical data.

2. Entities include patients, diseases, drugs, and side effects.

Named Entity Recognition (NER):

1. Extracts relevant entities from EHR text.

2. Utilizes NLP techniques to identify medical terms.

Entity Normalization and Ranking:

1. Standardizes entity representation.

2. Ranks entities based on importance and relevance.

Graph Neural Networks (GNNs) for Drug Interaction Prediction:

1. Applies deep learning techniques to predict interactions.

2. Uses Neo4j graph database for storage and querying.

**Implementation Details**

1. Programming Language: Python

2. Graph Database: Neo4j

**Libraries Used:**

spaCy, scikit-learn, pandas, networkx, DGL, PyTorch-Geometric

Neo4j for efficient graph storage and querying

**Installation & Setup**

Install Dependencies

1. pip install spacy pandas scikit-learn networkx dgl torch-geometric neo4j

2. Set Up Neo4j Database

3. Install and configure Neo4j.

4. Load the dataset and create relationships between entities.

**Run the Knowledge Graph Construction**

1. python build_knowledge_graph.py

2. Train Graph Neural Network for Drug Interaction Prediction

3. python train_gnn.py

**Usage**

1. Query the graph using Cypher queries in Neo4j.

2. Train GNN models to predict drug interactions.

3. Perform analysis on patient-disease-drug relationships.

**Applications**

1. Drug interaction prediction

2. Clinical decision support systems

3. Biomedical research & personalized medicine

**Contributors**

***Gaurav Mandloi***
