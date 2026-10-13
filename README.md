# AI-Interview-Assistant

## Setup

1. Copy `.env.example` to `.env`.
2. Replace the placeholder with your `GROQ_API_KEY`.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run locally:

```bash
streamlit run app.py
```

## Streamlit Community Cloud Deployment

1. Open the app settings in Streamlit Community Cloud.
2. Under Secrets, add your key using TOML syntax, for example:

```toml
GROQ_API_KEY = "gsk_your_api_key_here"
```

3. Deploy the app.

The app now reads `GROQ_API_KEY` from either a local `.env` file or `st.secrets` on Streamlit Cloud.

# Architecture

![Architecture diagram of venu-16/ai-interview-assistant](https://github.com/Venu-16/AI-Interview-Assistant/blob/main/AI%20interview%20Assitant%20architecture.png)
