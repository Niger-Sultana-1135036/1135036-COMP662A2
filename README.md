# Niger Sultana
## 1135036

Project: Develop a Natural-Hazard Land-Use Assistant that helps a landowner or junior planner
undertake a preliminary assessment. Your system will retrieve evidence from a curated collection of
national, regional, and district policy documents; integrate that evidence with structured site and
development information; and generate a transparent preliminary assessment. It must cite the
supporting document and clause, identify missing or uncertain information, and avoid presenting its
output as a formal resource-consent, building-consent, legal, or engineering decision.

Goal is to emphasis is on
building a technically sound RAG pipeline, optimising prompts systematically, evaluating retrieval and
generation separately, and critically analysing system limitations in a high-stakes policy context.

💻 --- SYSTEM INFO ---
Python Version: 3.14.3
Python Executable: c:\Users\HP\Documents\AI_Lincoln University\COMP662\1135036_Asignment2\COMP662.venv\Scripts\python.exe

📦 --- INSTALLED LIBRARIES ---
✅ pandas                 : 3.0.6
✅ numpy                  : 2.5.3
✅ pdfplumber             : 0.11.10
✅ pypdf                  : 6.19.0
✅ faiss                  : 1.15.1
✅ transformers           : 5.17.0
✅ huggingface_hub        : 1.33.0
✅ sentence_transformers  : 6.1.0
✅ torch                  : 2.14.0+cpu
✅ openpyxl               : 3.1.5

This notebook is built up task by task (1-5). Everything (code, results, analysis) lives here.

**How to run:** set the environment variable `COMP662_DATA_DIR`, install the pinned packages from `requirements.txt`, then *Run All*. Task 1 needs no model and no GPU; it takes a few seconds and regenerates everything in `processed/`.

