# AI Prompt Firewall

A lightweight middleware to protect LLM apps against:
- Prompt injection
- Data exfiltration attempts
- Malicious prompts

## Run
```bash
pip install -e .
uvicorn firewall.server:app --reload --port 8080
