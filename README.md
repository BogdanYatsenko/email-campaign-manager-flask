# EmailBot Pro

## Quick Start

**Python**
```bash
python -m venv .venv && . .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env  # Windows: copy .env.example .env
python app.py
```

**Docker**
```bash
docker build -t emailbot-pro .
docker run --env-file .env emailbot-pro
```


## 📝 License
Released under the **MIT License** © 2025 Bogdan Yatsenko.

📦 About the migration
This repository was migrated as part of my Portfolio Refresh. Originally developed locally; during migration I added README, .env.example, Docker/CI, and minor improvements.
