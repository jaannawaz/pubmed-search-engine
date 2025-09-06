# 🔬 PubMed Search Engine

A beginner-friendly Gradio application that searches PubMed and filters results to show only articles from high-impact journals based on Journal Impact Factor data. Perfect for students and researchers who want to focus on the most credible research.

## 🎯 Problem Solved

While mentoring students in Research Methodology Course, I noticed they struggled with finding high-quality articles on PubMed. Students were overwhelmed by thousands of search results and couldn't easily identify which journals were most credible and impactful for their research.

## ✨ Features

- **🔍 Intelligent PubMed Search**: Search with advanced filters
- **📊 Journal Impact Factor Filtering**: Show only articles from high-impact journals
- **🏆 Quartile Rankings**: Q1, Q2, Q3, Q4 journal categorization
- **📈 Smart Sorting**: Sort by JIF, quartile, or relevance
- **🎯 Research Filters**: Article type, human studies, open access
- **📱 Mobile Friendly**: Works great on all devices
- **⚡ Fast & Reliable**: Optimized API calls with error handling

## 🚀 Live Demo

**Try it now:** [https://huggingface.co/spaces/Babajaan/Pubmed_Search_Engine](https://huggingface.co/spaces/Babajaan/Pubmed_Search_Engine)

## 🛠️ Technology Stack

- **Frontend**: Gradio
- **Backend**: Python
- **Data Source**: PubMed (NCBI) API
- **Journal Data**: Journal Impact Factors 2024
- **Deployment**: Hugging Face Spaces

## 📋 Prerequisites

- Python 3.8+
- pip package manager

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jaannawaz/pubmed-search-engine.git
   cd pubmed-search-engine
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```

5. **Open your browser:**
   Navigate to `http://localhost:7860` (or the port shown in terminal)

## 📁 Project Structure

```
pubmed-search-engine/
├── app.py                          # Main application file
├── requirements.txt                 # Python dependencies
├── README.md                       # Project documentation
├── journal_impact_factors/         # Journal data directory
│   └── top_journals.json          # Journal impact factor data
└── .gitignore                     # Git ignore file
```

## 🔧 Configuration

### Environment Variables (Optional)

Create a `.env` file for API configuration:

```env
NCBI_TOOL_NAME=your-tool-name
NCBI_CONTACT_EMAIL=your-email@example.com
NCBI_API_KEY=your-api-key  # Optional, for higher rate limits
```

### Journal Data

The app uses journal impact factor data from `journal_impact_factors/top_journals.json`. This file contains:
- Journal names and aliases
- Impact factors
- Quartile rankings
- Categories

## 📖 Usage

1. **Enter your search query** (e.g., "diabetes prevention")
2. **Select filters:**
   - Article type (RCT, Meta-Analysis, etc.)
   - Humans only
   - Open access
   - Years back
   - Max results
3. **Choose journal filtering:**
   - Show only top journals (recommended)
   - Show all journals
4. **Select sorting option:**
   - Default (relevance)
   - JIF (High to Low)
   - Quartile (Q1 to Q4)
5. **Click "Search PubMed"**

## 🎓 Educational Value

This tool helps students and researchers:
- **Focus on credible sources** by filtering high-impact journals
- **Save time** by avoiding manual journal quality checks
- **Learn research methodology** through practical application
- **Understand journal rankings** and their significance

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **100x Engineer Course** for teaching Gradio app development
- **Siddhant Goswami** for the excellent Gradio session
- **PubMed/NCBI** for providing the research database
- **Journal Impact Factor data** from 2024 rankings

## 📞 Contact

If you have any questions or suggestions, please feel free to reach out!

---

**Built with ❤️ for the research community**