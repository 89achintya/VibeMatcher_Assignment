VibeMatcher Assignment — Achintya Tiwari
📌 Overview

This project is part of the Vibe Product Search Assignment.
It demonstrates how to generate product embeddings, perform similarity-based vibe searches, and handle fallback prompts for unmatched queries.

🧾 Dataset

File: vibe_products_preview.csv
Contains product descriptions and vibe-related text used to generate embeddings.

⚙️ Steps Performed

Load dataset

Generate embeddings (using a free local model for efficiency)

Find top similar products for a given vibe-based query

Implement fallback response for unmatched queries

Save final CSV with embeddings → vibe_products_with_embeddings.csv

🧩 Files Included

VibeMatcher_Assignment_Achintya_Tiwari.ipynb → Main code notebook

vibe_products_preview.csv → Input dataset

vibe_products_with_embeddings.csv → Output file with embeddings

🚀 How to Run

Open the notebook in Google Colab

Run all cells sequentially

The output file will be generated automatically

💬 Example Query
find_top_k("ultra futuristic metallic rave")


If no close match is found:

fallback_prompt("ultra futuristic metallic rave")

👨‍💻 Author

Achintya Tiwari
B.Tech in Electronics & Communication Engineering (GL Bajaj Institute of Technology & Management)
