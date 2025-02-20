<!-- Logo -->
<p align="center">
  <img src="assets/logo.png" alt="InboxHero Logo" width="600">
</p>

# InboxHero ✉️

**InboxHero** is a smart email prioritizer and Gmail assistant built with **Streamlit**, **Langchain**, and **ChatGroq**. It helps you quickly identify the most important emails in your inbox, detect those that need a reply, and even generate draft responses—all in one sleek, professional workspace.

---

## Demo Video - InboxHero 🎥

https://github.com/user-attachments/assets/YOUR_VIDEO_ID

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

### Contributing 🤝
Contributions are welcome! If you’d like to improve InboxHero or add new features, please fork the repository and submit a pull request.

### License 📄
This project is licensed under the Apache 2.0 License.