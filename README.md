# bellhaven-crm-assessment
   git clone https://github.com/dmaterna1/bellhaven-crm-sync.git
   cd bellhaven-crm-sync
   python3 -m venv .venv && source .venv/bin/activate
   pip install -r requirements.txt
   cp .env.example .env
   python -m src.pipeline run
