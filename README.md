<div align="center">
  <a href="https://brightdata.com/">
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/brightdata/logo/light.svg" width="300" alt="Bright Data Logo">
  </a>

# 🛍️ Amazon Product Analytics 1
Analyze Amazon product data and track market trends with AI-powered insights, interactive visualizations, and reliable data extraction across global marketplaces.

<img src="https://img.shields.io/badge/python-3.9+-blue" />
<img src="https://img.shields.io/badge/Gemini-API-blueviolet" />
<img src="https://img.shields.io/badge/License-MIT-blue" />
</div>

<div align="center">

https://github.com/user-attachments/assets/d6248647-4c3d-4bfc-a653-0ec79ae0d4a7

</div>

---

## 🎯 Key features
- **Multi-market analysis**. Deep insights from any of 23 Amazon marketplaces.
- **Fresh data**. Sourced via Bright Data’s [Amazon Scraper API](https://brightdata.com/products/web-scraper/amazon).
- **Interactive dashboard**. Charts for price distributions and rating analytics.
- **AI-powered insights**. Ask natural-language questions and get recommendations.
- **Deal detection**. Identify discounts and promotional opportunities.
- **Data export**. Download CSVs for further analysis and reporting.

## 💡 Use cases
- **Product research**. Find the best value products in your target market.
- **Price analysis**. Understand pricing distribution and competitive positioning.
- **Deal hunting**. Identify genuine discounts and promotional opportunities.
- **Quality assessment**. Analyze ratings vs price to find sweet spots.
- **Market positioning**. See where products rank in search results.
- **Purchase decisions**. Get AI-powered recommendations for buying choices.

## 🎯 How it works
- **Select your market**. Choose your target marketplace from 23 global regions, including the US, Canada, UK, Germany, Japan, India, and more. Each market uses local currency and pricing.
- **Search products**. Enter keywords (e.g., "wireless headphones", "iPhone 15", "coffee maker") or select from popular searches.
- **Get intelligent analysis**. Comprehensive market insights automatically generated, including price distribution patterns, quality vs price analysis, deal intelligence, value scoring, competitive positioning, and search rankings.
- **Receive smart recommendations**. AI-powered product picks for best overall value, highest rated options, and best deals with significant savings.
- **Use AI assistant**. Ask natural language questions like "Which product offers the best value for money?" or "Show me highly-rated options under $50".
- **Filter and export**. Filter by price ranges, Prime eligibility, ratings, and deals, then export to CSV for in-depth analysis.

## 🌍 Supported Amazon markets
Choose from 23 major marketplaces:
- **North America**. United States, Canada, Mexico.
- **Europe**. United Kingdom, Germany, France, Italy, Spain, Netherlands, Sweden, Poland.
- **Asia pacific**. Japan, Australia, India, Singapore.
- **Other regions**. Brazil, Ireland, Belgium, Turkey, UAE, Saudi Arabia, Egypt, South Africa.

> *Note:* The app supports one marketplace at a time to reflect local pricing, ranking, and availability differences.


## 🚀 Quick start

### Prerequisites

- **Python 3.9+** – [download here](https://www.python.org/downloads/)
- **Bright Data API key** – [get your API key](https://docs.brightdata.com/api-reference/authentication#how-do-i-generate-a-new-api-key%3F)
- **Google Gemini API key** – [generate API key](https://aistudio.google.com/apikey)

### Installation

```bash
# Clone the repository
git clone https://github.com/triposat/amazon-product-analytics.git
cd amazon-product-analytics

# Install dependencies
pip install -r requirements.txt

# Configure API credentials
cp .env.example .env
# Edit .env file and add your API keys
```

### Configuration

Set up your environment variables:
```bash
BRIGHT_DATA_API_KEY=your_bright_data_api_key_here
GEMINI_API_KEY=your_google_gemini_api_key_here
```

### **Launch application**

```bash
# Start the dashboard
streamlit run streamlit_app.py

# Alternative: Use the run script
./run_app.sh
```

🎉 **Access your dashboard at:** [http://localhost:8501](http://localhost:8501/)

## 🛠️ Technology stack

| Component          | Technology                                                                                         | Purpose                         |
| ------------------ | -------------------------------------------------------------------------------------------------- | ------------------------------- |
| **Frontend**       | [Streamlit](https://streamlit.io/)                                                                 | Interactive web dashboard       |
| **Data source**    | [Bright Data Amazon Scraper API](https://brightdata.com/products/web-scraper/amazon) | Reliable Amazon data collection |
| **Processing**     | [Pandas](https://pandas.pydata.org/)                                                               | Data analysis and manipulation  |
| **Visualizations** | [Plotly](https://plotly.com/python/)                                                               | Interactive charts and graphs   |
| **AI integration** | [Google Gemini](https://ai.google.dev/)                                                            | Natural-language insights       |
| **HTTP + retries** | [Requests](https://pypi.org/project/requests/) + [Tenacity](https://pypi.org/project/tenacity/)    | Robust API communication        |

## 📚 Additional resources
1. Deep-dive examples – explore Bright Data's *Amazon Scraper* samples & usage patterns [in this guide repo](https://github.com/luminati-io/Amazon-scraper)
2. Need data fast? – use [Amazon Datasets](https://brightdata.com/products/datasets/amazon) for fresh, validated data with multiple delivery formats
3. Compare tools – see this [overview of popular Amazon scrapers](https://brightdata.com/blog/web-data/best-amazon-scrapers) and where each fits

## 🤝 Support
Need help? We're here to assist. [Contact us now](https://brightdata.com/contact).
