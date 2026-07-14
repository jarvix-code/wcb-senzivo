# WCB Enterprise

Unbranded WCB-Gateway + Dashboard Kernel Distribution.

## Repositories

Dieses Repo enthaelt die WCB-Engine-Komponenten ohne Firmen-Identitaet.

## Components

| Component | Description |
|-----------|-------------|
| senzivo-dashboard | Dashboard-Backend (main.py) + Frontend (dist/) |
| .wcb/ | WCB-Gateway Konfiguration |
| tools/ | Kernel + System-Tools |

## Setup

```bash
# Dashboard
cd apps/dashboard/backend
python3 -m venv .venv
pip install -r requirements.txt
python3 main.py

# Kernel
python3 tools/bojare_kernel.py health
```

## License

Proprietary. Contact: jarvix-code
## Extension Repos

Separate extension repos (firmenspezifisch, nicht Teil der WCB-Distribution):
- https://github.com/jarvix-code/senzivo-docs
- https://github.com/jarvix-code/senzivo-fritzbox  
- https://github.com/jarvix-code/senzivo-analytics
- https://github.com/jarvix-code/senzivo-arztbrief
- https://github.com/jarvix-code/senzivo-pipeline-ui
