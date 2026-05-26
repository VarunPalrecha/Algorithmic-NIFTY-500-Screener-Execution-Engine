# Algorithmic-NIFTY-500-Screener-Execution-Engine
NIFTY 500 Screener Using Dhan Data API

⚙️ Configuration & Usage
Step 1: Configure Broker API
Before running the code, you must initialize the dhan object in your script using your specific API credentials. Ensure your broker API connection is authorized:
**from dhanhq import dhanhq

# REPLACE with your actual Client ID and Access Token
client_id = "YOUR_DHAN_CLIENT_ID"
access_token = "YOUR_DHAN_ACCESS_TOKEN"
dhan = dhanhq(client_id, access_token)**

Step 2: Ensure Symbol List is Available
The script expects a local mapping file to match NSE symbols with the broker's internal security IDs.
Ensure Symbol List NSE.xlsx (or its CSV equivalent) is placed in the working directory (e.g., /content/ if using Google Colab).

⚠️ Disclaimer
This project is for educational and research purposes only. The algorithms and scripts do not constitute financial advice. Algorithmic trading involves significant risk, and backtested results do not guarantee future performance. Always test strategies in a paper-trading environment before deploying real capital.
