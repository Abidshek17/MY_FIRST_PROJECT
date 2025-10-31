
# AI-Based Congestion Control in SDN — Submission Package (v13.4.2)

University: MMMUT Gorakhpur  
Team: Aditya Kumar Maurya, Sujal Gupta, Abhishek Yadav  
Guide: Mr. Vimal Kumar

## Contents
- **AI_Congestion_Report.pdf** — Final report (compile with `make pdf` if you need to regenerate).
- **code_clean.zip** — Cleaned project source for evaluation (no large caches, node_modules, or build artifacts).

## How to Run (quick)
1) Unzip `code_clean.zip`
2) Open a terminal in the extracted folder and run:
   ```bash
   make up
   python3 docker/images/backend/ai/train_model.py
   make plots
   make report
   make pdf
   make down
   ```
   - Frontend: http://localhost:3000  
   - Backend: http://localhost:5000  

## Notes
- JWT-only backend (`/login_jwt`, `/refresh`).
- Email alerts use Gmail App Password (optional).
- Overleaf PDF compiles to `overleaf/build/AI_Congestion_Report.pdf`.

