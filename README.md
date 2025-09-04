# AI-Powered Web Scraping Agent with Natural Language Instructions (AI Travel Planner 🌎✈️)

This project demonstrates an advanced AI-powered web scraping agent that uses natural language instructions to gather data from the web. The agent leverages a combination of real-time and historical data to provide contextual, personalized, and relevant insights based on user input. It uses Large Language Models (LLMs), web scraping techniques, and automated browser interaction to fulfill various tasks, such as finding information, gathering statistics, and extracting data from different online sources.

## Features

### 🔍 Smart Web Scraping
- Single-input natural language processing for web scraping tasks
- Intelligent parsing of user instructions and data requirements
- Real-time scraping from various websites
- Progress tracking for scraping operations

### 🤖 AI-Powered Assistants
- **Scraping Assistant**: Helps with extracting specific data or information from the web
- **Research Assistant**: Provides insights and context on scraped data
- Integration with web scraping tools to gather real-time data from multiple sources

### 📊 Data Collection & Insights
- Extraction of detailed information from websites
- Summarized results from gathered data
- Contextual insights and reports based on scraped content
- Extraction of structured data for further analysis

### 💬 Interactive Chat Interface
- Natural conversation with AI assistants
- Suggested prompts for easy starting points
- Context-aware responses based on web scraping tasks
- Rich formatting for clear information display

## Technical Stack

- **Frontend**: Streamlit
- **Language Models**: Ollama/Claude
- **Web Scraping Tools**: BrightData, BeautifulSoup, Selenium
- **Search**: DuckDuckGo API
- **Data Storage**: JSON + Vector Database
- **Web Data (Realtime, Datasets, Scraping)**: BrightData

## Getting Started

1. **Install Dependencies**
```bash
pip install -r requirements.txt
```

2. **Environment Setup**
```bash
# Create a .env file with necessary API keys and configurations
cp sample.env .env
```

3. **Initialize the Application**
```bash
cd frontend
streamlit run frontend.py
```

4. **Run the Backend**
```bash
cd backend
python app.py
```

## Usage

1. **Provide Travel Instructions**
   - Simply describe your trip using natural language.
   - Example: `I want to visit Bangkok from New York between July 1st and July 10th`

2. **Explore Your Results**
   - View available flight options and their pricing.
   - Discover hotel suggestions based on your preferences.
   - Browse local restaurant recommendations.

3. **Get Local Insights**
   - Chat with the Research Assistant for insights on nearby attractions.
   - Receive personalized restaurant suggestions.
   - Learn about local customs, culture, and useful travel tips.

