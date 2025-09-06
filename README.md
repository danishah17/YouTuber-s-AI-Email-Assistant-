#  YouTuber's AI Email Assistant  

This project is an **AI-powered email automation workflow** built with [n8n](https://n8n.io/), [OpenAI](https://openai.com/), and [Gmail](https://mail.google.com/).  
It helps YouTubers automatically **classify, draft, and respond** to important emails, such as **sponsorships** and **high-priority requests**.  

---

##  Features
-  **Gmail Trigger** – Listens for incoming emails in real-time.  
-  **Text Classifier** – Categorizes emails as *Sponsorship* or *High Priority*.  
-  **OpenAI Chat Model** – Generates context-aware responses:
  - Sponsorship emails: Professional reply with cost/package details.  
  - High-priority emails: Quick and helpful responses.  
-  **Draft Creation** – Automatically saves replies as **drafts in Gmail** for review.  

---

##  Workflow Overview
1. **Trigger**: Gmail receives an email.  
2. **Classification**: Text Classifier sorts it into categories.  
3. **Response Generation**: OpenAI model drafts a reply.  
4. **Draft Creation**: Reply is stored in Gmail as a draft, ready to send.  


---

##  Files
- `My workflow.json` → The complete n8n workflow file.  
- `Youtuber's Email Assistant.png` → Workflow diagram.  

---

##  Setup
1. Import `My workflow.json` into n8n.  
2. Connect your **Gmail** and **OpenAI** credentials.  
3. Activate the workflow.  

---

##  Use Case
Perfect for **YouTubers, creators, and influencers** who receive frequent sponsorships and urgent collaboration requests.  
This assistant ensures no important email goes unanswered.  

---

##  Contribute
Feel free to fork, open issues, or suggest improvements!  
