ASSIGNMENT 2 - PYTHON IMPLEMENTATION

This is a dependency-free Python version of the E-Commerce capability composition example. It reads the included formal JSON dataset and demonstrates state, goal, and capability encoding, directional compatibility, typed input/output checks, composition, cosine similarity, goal relevance, and operational attributes.

The complete assignment materials are included:
- DELIVERABLE_1_FORMAL_EMBEDDING_DESIGN.md
- capability_embedding.py (Deliverable 2 implementation)
- ecommerce_purchase_flow.json and DELIVERABLE_3_EXPERIMENTAL_DATASET.md
- DELIVERABLE_4_TECHNICAL_REPORT.md

REQUIREMENTS
- Python 3.10 or newer
- No pip packages required

RUN ON WINDOWS
1. Extract the project folder.
2. Open Command Prompt or PowerShell in that folder.
3. Run all five experiments:
   py -3 capability_embedding.py --experiments
   If `py` is unavailable, use `python capability_embedding.py --experiments`.
4. Show all encodings:
   py -3 capability_embedding.py --vectors
5. Display a composed purchase capability:
   py -3 capability_embedding.py --compose
6. Combine options:
   py -3 capability_embedding.py --experiments --vectors --compose

The default dataset is ecommerce_purchase_flow.json. To use another compatible JSON file, pass its path after the script name.

The assignment PDF remains authoritative. The report documents assumptions and limitations, including Boolean-only vector state encoding and the fact that similarity is not a compatibility test.
