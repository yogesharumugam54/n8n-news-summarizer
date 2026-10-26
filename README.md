## Setup (credentials)

This workflow does not include any API keys. Add your own after importing:

1. In n8n choose **Import from file** and select `workflow.json`.
2. **Google Gemini Chat Model**: create a credential and paste your own
   Gemini API key (from Google AI Studio).
3. **Create Tweet (X)**: connect your own X (Twitter) developer credentials.
   Posting requires X API access, which has its own limits and costs.
4. Click **Execute workflow** to test, then switch it to **Active**.

Never commit or share API keys. Keep them in n8n credentials or in a `.env` file.


## Data sources
- BBC Technology RSS: https://feeds.bbci.co.uk/news/technology/rss.xml
- BBC Business RSS: https://feeds.bbci.co.uk/news/business/rss.xml

To use other sources, change the URL in the **RSS Read** nodes.