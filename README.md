# IP-Reputation-Checker
A Python command-line tool that checks the reputation of any IP address using the **AbuseIPDB** API — a real, industry-used threat intelligence database.

## Features
- Real-time IP reputation lookup
- Abuse confidence score (0–100%)
- Total number of abuse reports for the IP
- Country and ISP information
- Risk level classification (Low / Medium / High)

## Setup

1. Create a free account at [AbuseIPDB](https://www.abuseipdb.com/register)
2. Generate an API key from your account dashboard
3. Add your API key in `checker.py`:
```python
   API_KEY = "your_api_key_here"
```

## How to Use

```bash
pip install requests
python checker.py
```

Enter any IP address when prompted, and the tool will display its abuse score, report history, and risk classification.

## Example Output
