# Overills — Production Report Processor

Upload Jalna Dosomat D20.8 PDF reports and download a summary Excel file.

## Deploy to Railway (free hosting)

### Step 1 — Create a GitHub repo
1. Go to https://github.com/new
2. Name it `overills`, keep it private, click **Create repository**
3. Upload all these files to the repo (drag & drop them on the GitHub page)

### Step 2 — Deploy on Railway
1. Go to https://railway.app and sign up (free, no credit card)
2. Click **New Project → Deploy from GitHub repo**
3. Select your `overills` repo
4. Railway will auto-detect Python and build the app
5. Once deployed, click **Settings → Networking → Generate Domain**
6. Your app is live at `https://overills-xxxx.railway.app`

### That's it!
Open the URL, drop your PDFs in, and download the Excel file.

## Local development
```bash
pip install -r requirements.txt
python app.py
# Open http://localhost:5000
```
