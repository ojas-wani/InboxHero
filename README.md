<!-- Logo -->
<p align="center">
  <img src="assets/logo.png" alt="InboxHero Logo" width="600">
</p>

# InboxHero ✉️

**InboxHero** is a smart email prioritizer and Gmail assistant built with **Streamlit**, **Langchain**, and **ChatGroq**. It helps you quickly identify the most important emails in your inbox, detect those that need a reply, and even generate draft responses—all in one sleek, professional workspace.

---

## Demo Video - InboxHero 🎥

https://github.com/user-attachments/assets/8e79293d-2659-4a83-bdfc-bbc185120fdf

---

## Features 🚀

- **Email Prioritization:**  
  - Automatically fetches your Gmail inbox and filters out promotional emails.
  - Uses a custom ranking prompt with a language model to score emails from 1 (least important) to 10 (extremely important).

- **Reply Detection & Draft Generation:**  
  - Detects emails that require a reply and displays them in a dedicated section.
  - Offers an interactive "Generate Draft" button to quickly produce draft responses.

- **Content Summarization:**  
  - Summarizes the email body using **ChatGroq** and **Langchain**, ensuring a concise and clear overview.
  - Cleans and organizes summaries for a crisp, readable display.

- **Microsoft Attachments Support:**  
  - Reads and summarizes various Microsoft attachments such as PDFs, DOCX, Excel sheets, and more.
  - Presents attachment summaries using beautiful Markdown formatting for a professional look.

- **Interactive Chat Mode:**  
  - Engage with your inbox through a conversational chat interface.
  - Ask queries and receive real-time insights about your emails.

- **Customizable Time Frame:**  
  - Choose from multiple time windows (e.g., 1 Hour, 6 Hours, 24 Hours, etc.) to filter emails based on recency.

- **Seamless Integration:**  
  - Powered by **Langchain**🦜 for advanced prompt management and natural language processing.
  - Utilizes robust Python libraries like Streamlit, simplegmail, and python-dotenv for a smooth user experience.

---

## Installation & Setup 🔧

**Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/inboxhero.git
   cd inboxhero
   ```

### Install Dependencies:

```bash
pip install -r requirements.txt
```
## 📌 Get Your LangChain Groq API Key

To use LangChain with Groq, you need an API key. Follow these steps:

1. **Go to the Groq Console**: [Click here to get your API key](https://console.groq.com/playground)
2. **Sign in or Sign up** if you haven't already.
3. **Generate an API key** and copy it.
4. **Set up the key in your environment**:
   - If running locally, add it to your `.env` file:
     ```ini
     GROQ_API_KEY=your_api_key_here
     ```
   - If deploying to a cloud service, add it to **your environment variables or repository secrets**.

✅ Now, you're all set to use Groq with LangChain! 🚀


## 📌 Get Your Gmail Client Secret JSON File

To connect to your Gmail account, you need a **Client Secret JSON file**. Follow these steps:

1. **Go to Google API Console**: [Follow this guide to download your client secret file](https://stackoverflow.com/questions/52200589/where-to-download-your-client-secret-file-json-file#:~:text=Go%20to%20your%20Google%20API%20Console%20where%20you%27ll,arrow%20on%20the%20farthest%20right%20of%20the%20page%3A)
2. **Enable the Gmail API** for your Google Cloud project.
3. **Download the `client_secret.json` file** from the Credentials section.
4. **Upload the file when you run the streamlit app**.

✅ Now, you're ready to authenticate and interact with Gmail in your app! ✉️


### Contributing 🤝
Contributions are welcome! If you’d like to improve InboxHero or add new features, please fork the repository and submit a pull request.

### License 📄
This project is licensed under the Apache 2.0 License.