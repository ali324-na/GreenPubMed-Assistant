# 🧬 GreenPubMed Assistant

Assistant de recherche médicale utilisant le **RAG** (Retrieval-Augmented Generation) optimisé pour la sobriété numérique.

## 🌿 Objectif Green IT
L'objectif est de fournir des réponses précises aux questions médicales (Diabète, Maladies respiratoires) tout en minimisant l'impact carbone du pipeline de données.

### 🏗️ Architecture du Projet
*   **Data Engineering (Track 1) :** Passage du format CSV au **Parquet Snappy** pour réduire le stockage et le temps de lecture.
*   **AI Implementation (Track 2) :** Utilisation d'embeddings locaux et d'un index **FAISS** pour éviter les appels API énergivores vers le Cloud.

## 📊 Benchmarks de Sobriété
*   **Gain de stockage :** -76% d'émissions de CO2 lors de l'écriture en Parquet.
*   **Rapidité :** Recherche sémantique en moins de 0.1 seconde.

## 🛠️ Installation
```bash
pip install -r requirements.txt
