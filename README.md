# 🤰 MaternalCare_AI

**MaternalCare_AI** is a lightweight, domain-specific AI assistant that delivers accessible and localized maternal health guidance using ZIP Code data, structured vulnerability indicators, and a curated knowledge base.

---

## 🧠 Key Features

- **Localized Health Answers**: Delivers insights based on ZIP Code Tabulation Area (ZCTA) using CDC's Social Vulnerability Index (SVI)
- **Retrieval-Augmented Generation (RAG)**: Combines vector search with a QA pipeline over maternal health documents
- **Gradio Interface**: Easy-to-use frontend for real-time maternal care Q&A
- **Low-Resource Deployment**: Runs in Google Colab for accessible prototyping

---

## 🗃️ Project Files

| File | Description |
|------|-------------|
| `MD_Data_Miner_ITAI2377.ipynb` | Main AI pipeline (Colab-compatible) |
| `kb_docs.csv` | Embedded maternal health knowledge base |
| `SVI_2022_US_ZCTA.csv` | Social Vulnerability Index data |
| `Maternal Health Risk Data Set.csv` | Risk classification data |
| `Golden_QA_Semantic_Evaluation.csv` | QA evaluation test set |

---

## 🚀 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the required CSV files listed above.
3. Run all cells to load data, build the knowledge base, and launch the Gradio interface.
4. Ask maternal health questions like:
   - “Where can I get low-cost maternal health support?”
   - “What are signs of postpartum depression?”

---

## 🔗 Demo Link

[**▶️ Launch in Google Colab**](https://colab.research.google.com/drive/1MX0kwCxK5brkt1laZO83Gxxz3PeOJ-F9)

## 🧑‍🤝‍🧑 Authors

- Binte Zahra

---

## 📄 License

MIT License — use freely with attribution.
