# 🌍 Wikipedia City Travel Guide Generator  

This project scrapes **Wikipedia city pages** using **BeautifulSoup**, extracts text from all relevant links, and then leverages **Google Gemini API** to generate a **beautifully formatted travel guide**.  

---

## 🚀 Features
- Scrapes a given Wikipedia city page  
- Extracts:
  - ✅ Page Title  
  - ✅ Main Page Text  
  - ✅ Relevant Internal Links (ignores files/images)  
- Uses **Gemini 2.5 Flash** to:  
  1. Filter only travel-related links (museums, landmarks, attractions, history, etc.)  
  2. Generate a **well-formatted city travel guide** in Markdown  

---

## ⚙️ Installation

```bash
# Clone and enter the project
git clone https://github.com/abdlmd/wikipedia-travel-guide.git
cd wikipedia-travel-guide

# Create and activate a virtual environment
python -m venv venv
# Mac/Linux:
source venv/bin/activate
# Windows:
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Create a .env file with your API key (or add this line to .env)
# GEMINI_API_KEY=your_api_key_here

# Run the project
jupyter lab
