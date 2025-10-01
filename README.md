# dkorchun-n8n-projects

**Denis Korchun’s n8n Automations** – Real-world workflows designed and implemented by Denis.  

## Lab 1: Reddit Scraper Integration  

**Automate subreddit monitoring and data extraction with n8n.**  

### 🔍 Project Overview  
This workflow connects n8n to Reddit’s API to:  
- Monitor specified subreddits for new posts  
- Extract post metadata (title, author, timestamp, content)  
- Save results to Google Sheets or a database of your choice  (to be done)

### ✨ Key Features  
- OAuth2 authentication with Reddit  
- Configurable subreddit list via environment variables  
- Built-in rate-limit handling and retry logic  
- Modular design for easy extension (e.g., alerting, AI analysis)

- ![Workflow Diagram](1-workflow.png)

### 📖 Usage  
- Scraped posts appear in the configured Google Sheet  (to be done)
- Customize further nodes for notifications, downstream processing, or AI-based analysis  

### 📄 License  
MIT License  

***

*Built and maintained by Denis Korchun for practical n8n automations.*
