# 📊 AI Data Analysis Agent

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-latest-red.svg)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-green.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

An intelligent AI data analysis agent built using the **Phidata framework** and **OpenAI's GPT-4** model. This agent helps users analyze their data (CSV, Excel files) through natural language queries, powered by OpenAI's language models and DuckDB for efficient data processing - making data analysis accessible to users regardless of their SQL expertise.

## ✨ Features

- 📤 **Smart File Upload**: 
  - Support for CSV and Excel files
  - Automatic data type detection and schema inference
  - Intelligent data preprocessing and cleaning
  - Handle missing values and data formatting

- 💬 **Natural Language Queries**: 
  - Convert plain English questions into SQL queries
  - Get instant, accurate answers about your data
  - No SQL or programming knowledge required
  - Context-aware query understanding

- 🔍 **Advanced Analysis Capabilities**:
  - Perform complex data aggregations and calculations
  - Filter, sort, and group data intelligently
  - Generate comprehensive statistical summaries
  - Create insights and data-driven recommendations

- 🎯 **Interactive Web Interface**:
  - Clean, user-friendly Streamlit interface
  - Real-time query processing and results
  - Clear, formatted result presentation
  - Responsive design for all devices

- 🚀 **Performance & Reliability**:
  - Fast in-memory processing with DuckDB
  - Efficient handling of large datasets
  - Error handling and query validation
  - Secure API key management

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **AI Framework**: Phidata
- **Language Model**: OpenAI GPT-4
- **Database**: DuckDB (in-memory analytics)
- **Data Processing**: Pandas
- **File Handling**: Multiple format support

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- OpenAI API key ([Get one here](https://platform.openai.com))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pcstack7/ai-data-analysis-agent.git
   cd ai-data-analysis-agent
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   # Using Python module (recommended)
   python -m streamlit run ai_data_analyst.py
   
   # Or if streamlit is in your PATH
   streamlit run ai_data_analyst.py
   ```

4. **Open your browser**
   - The app will automatically open at `http://localhost:8501`
   - If not, navigate to the URL shown in your terminal

## 📖 How to Use

1. **🔑 API Key Setup**
   - Enter your OpenAI API key in the sidebar
   - The key is stored securely in your session

2. **📂 Upload Your Data**
   - Click "Browse files" to upload a CSV or Excel file
   - The app will automatically process and display your data
   - View column names and data preview

3. **💬 Ask Questions**
   - Type your question in natural language
   - Examples:
     - "What is the average sales by region?"
     - "Show me the top 5 customers by revenue"
     - "How many orders were placed last month?"
     - "What's the correlation between price and quantity?"

4. **📊 View Results**
   - Get instant answers with formatted results
   - See the generated SQL query (for learning)
   - Download or copy results as needed

## 📝 Example Queries

- **Basic Statistics**: "What's the summary statistics for all numeric columns?"
- **Filtering**: "Show me all records where sales > 1000"
- **Grouping**: "Group by category and show total revenue"
- **Sorting**: "Show top 10 products by profit margin"
- **Time Analysis**: "What's the monthly trend in sales?"
- **Comparisons**: "Compare performance between regions"

## 🔧 Configuration

### Environment Variables (Optional)
You can set your OpenAI API key as an environment variable:
```bash
export OPENAI_API_KEY="your-api-key-here"
```

### Customization
- Modify `ai_data_analyst.py` to add custom analysis functions
- Update the system prompt for different analysis styles
- Add new data visualization capabilities

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes**
4. **Commit your changes**: `git commit -m 'Add amazing feature'`
5. **Push to the branch**: `git push origin feature/amazing-feature`
6. **Open a Pull Request**

### Development Setup
```bash
# Clone your fork
git clone https://github.com/pcstack7/ai-data-analysis-agent.git
cd ai-data-analysis-agent

# Install in development mode
pip install -r requirements.txt

# Run the app
python -m streamlit run ai_data_analyst.py
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Troubleshooting

### Common Issues

1. **"streamlit command not found"**
   - Use: `python -m streamlit run ai_data_analyst.py`
   - Or add Python Scripts to your PATH

2. **Import errors**
   - Make sure all dependencies are installed: `pip install -r requirements.txt`
   - Check Python version compatibility

3. **OpenAI API errors**
   - Verify your API key is correct
   - Check your OpenAI account has credits
   - Ensure API key has proper permissions

4. **File upload issues**
   - Supported formats: CSV, XLSX
   - Check file encoding (UTF-8 recommended)
   - Ensure file size is reasonable

### Getting Help
- Open an issue on GitHub
- Check existing issues for solutions
- Join our community discussions

## 🙏 Acknowledgments

- [Phidata](https://github.com/phidatahq/phidata) for the excellent AI agent framework
- [Streamlit](https://streamlit.io/) for the amazing web app framework
- [OpenAI](https://openai.com/) for the powerful language models
- [DuckDB](https://duckdb.org/) for fast analytical processing

## 🌟 Star History

If you find this project useful, please consider giving it a star! ⭐

---

**Made with ❤️ by [pcstack7](https://github.com/pcstack7)**

