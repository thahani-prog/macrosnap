# MacroSnap
Snap a meal photo (or describe it), get calories and macros from Gemini, then text yourself a recap on WhatsApp via Twilio.

## Run locally
1. `pip install -r requirements.txt`
2. Copy `.streamlit/secrets.toml.example` to `.streamlit/secrets.toml` and fill in real values.
3. `streamlit run app.py`

## Deploy
Push to GitHub (never commit secrets.toml), deploy on Streamlit Community Cloud, and paste the secrets into the app's Secrets settings.
