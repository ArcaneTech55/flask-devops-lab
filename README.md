# Flask DevOps Lab - Version A

## Usage

```bash
source .venv/bin/activate
pip install -r requirements.txt
python3 app.py
```

- `/api/health` returns the health status of the app.
- `/api/config` returns the app configuration from config.json.
- `/api/report` returns the hostname, Python version, and app uptime.
