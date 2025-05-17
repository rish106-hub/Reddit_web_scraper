<b><u>Reddit Web Scraper AI Agent using n8n</u></b>  
<i>Automated Reddit data collection using visual workflows</i>  
<br><br>

<b>📌 Project Overview</b><br>
This project showcases a no-code/low-code AI agent built using <b>n8n</b>, designed to scrape posts from <b>Reddit</b> based on specific subreddits or keywords. The agent automates the retrieval of Reddit content and processes it for further use, such as data analysis, summaries, alerts, or storage.

<br><br>

<b>🔧 Tech Stack</b><br>
- <b>n8n</b> (Open Source Workflow Automation Tool)  
- <b>Reddit API</b> via HTTP Request Node  
- <b>JavaScript</b> functions within n8n  
- <b>Schedule Trigger</b> for automated runs  
- (Optional) <b>Telegram / Email / Google Sheets</b> for output destinations  

<br><br>

<b>📂 Features</b><br>
- Connects to Reddit via public API  
- Fetches data from any subreddit (e.g., <i>r/technology</i>, <i>r/worldnews</i>)  
- Filters and parses JSON data from Reddit  
- Formats output using n8n Function node  
- Runs on a schedule (e.g., every 30 minutes)  
- Sends results to desired destinations (webhook, email, DB, etc.)

<br><br>

<b>🛠️ How It Works</b><br>
1. <b>Trigger Node</b>: Starts the flow on a schedule or manually  
2. <b>HTTP Request Node</b>: Fetches data from Reddit's API  
3. <b>Function Node</b>: Filters, maps, or processes post titles & URLs  
4. <b>Output Node</b>: Saves, sends, or displays the processed data  

<br><br>

<b>📸 Screenshots</b><br>
Link :- https://drive.google.com/file/d/1Ap5Cd_nU_Jup5l2Rsj7K6q_a6hxGN-hA/view?usp=sharing
<i>n8n visual workflow for Reddit scraping</i>

<br><br>

<b>📦 Workflow File</b><br>
You can import the workflow using the `.json` file provided in this repository.  
<br>
To import:
1. Open your local/self-hosted n8n instance  
2. Click on "Import" and upload the `My_workflow.json` file  
3. Set up any required credentials or environment variables  

<br><br>

<b>📈 Use Cases</b><br>
- Market sentiment analysis based on subreddit activity  
- Trend tracking in niche communities  
- Academic research on online discussions  
- Content repurposing for blogs or newsletters  

<br><br>

<b>👨‍💻 Developer Notes</b><br>
- Built using the free/self-hosted version of <b>n8n</b>  
- Reddit API used without OAuth (public endpoints only)  
- Can be easily extended to support more complex actions (e.g., AI summarization)

<br><br>

<b>🤝 Connect With Me</b><br>
Created by <b>Rishav</b>  
📧 Email: rishavdewan10@gmail.com  
🌐 LinkedIn: RISHAV DEWAN (https://www.linkedin.com/in/rishav-dewan/)
⭐ If you find this useful, consider giving this repo a star!
