# AI Recruiter Intelligence & Outreach Automation

An end-to-end AI-powered recruiter discovery and LinkedIn outreach automation system built using n8n.

---

## 🔍 What It Does

1. Detects companies actively hiring (sector-based search)
2. Extracts structured hiring insights using AI
3. Identifies relevant HR / Talent Acquisition professionals
4. Filters recruiters using a scoring algorithm
5. Stores validated recruiters in MongoDB
6. Generates personalized LinkedIn outreach messages
7. Syncs conversations and detects recruiter replies
8. Automatically:
   - Sends follow-ups
   - Schedules meetings via Google Calendar
   - Updates conversation state

---

## ⚙ Nodes Used

- Schedule Trigger
- Code (JavaScript)
- Tavily Search
- Google Gemini (AI Model)
- MongoDB (Insert, Find, Update)
- Split In Batches
- IF (Conditional Logic)
- Linked API (Send Message, Sync Conversation)
- Google Calendar Tool
- Set / Edit Fields

---

## 📁 File

- `ai-recruiter-intelligence-automation.json` – Full n8n workflow export

---

## Note

LinkedIn messaging APIs are restricted for individual developers.  
Where direct API access is unavailable, simulation nodes are used for architectural design.
