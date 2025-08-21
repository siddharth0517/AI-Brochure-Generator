# AI Brochure Generator 📰🤖
## 📌 Overview

The AI Brochure Generator is an **AI-powered** project that creates **professional brochures** directly from a company’s website. It combines web scraping and **Large Language Models (LLMs)** to fetch company details, identify useful links (About, Careers, etc.), and automatically generate well-structured brochure content.

This tool helps automate the process of making brochures for marketing, branding, or recruitment purposes.

# 🚀 Features

+ Scrapes company websites to collect relevant information.

+ Filters important company links (About, Careers, Contact, etc.) using LLM reasoning.

+ Generates a ready-to-use brochure with titles, highlights, and descriptions.

+ Supports multiple companies by just providing different URLs.

+ Runs inside Jupyter Notebook for experimentation and easy customization.

# 🛠️ Tech Stack

+ Python

+ BeautifulSoup4 → Web scraping

+ Requests → Fetch webpage content

+ OpenRouter API → Access Dolphin Mistral LLM (cognitivecomputations/dolphin-mistral-24b-venice-edition)

+ dotenv → Environment variable handling

+ IPython.display → Render outputs inside Jupyter


# ▶️ Usage

+ Run the notebook:

+ jupyter notebook

Open AI Brochure Generator.ipynb.

+ Enter a company website URL.

+ Run the notebook cells step by step.

+ Get an AI-generated brochure instantly.

# 📊 Example Output

For a company website, the tool generates a brochure like:

Company Name: Example Tech Solutions
About Us: "We are a global leader in AI-driven automation..."
### Key Highlights:

+ Cutting-edge AI products

+ Career opportunities worldwide

+ Customer-first approach

# 💡 Future Enhancements

+ Export brochures in PDF/Word format.

+ Add multi-language support.

+ Build a Streamlit UI for easier interaction.

+ Support for multiple LLM providers.

# 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

# 📜 License

This project is licensed under the MIT License.
