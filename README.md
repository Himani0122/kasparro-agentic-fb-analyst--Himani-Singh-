# Kasparro — Agentic Facebook Performance Analyst: Himani Singh

## 🚀 Quick Start
This system autonomously diagnoses ROAS drops and generates creative recommendations using the Gemini API.

```bash
python -V  # should be >= 3.10
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
# This is the exact command used for the final output:
python src/run.py "Analyze ROAS drop in the last 7 days and propose new creative messaging for low-CTR ads"