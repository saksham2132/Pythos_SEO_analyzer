

📊 Pythos SEO Analyzer

A lightweight Python-based SEO crawler and analyzer that scans web pages and generates detailed SEO insights including links, metadata, headings, and structural issues.

🚀 Features
🔎 Crawl and analyze any website URL
📄 Extract page title, meta description, and keywords
🔗 Detect internal and external links
🧱 Analyze heading structure (H1–H6)
⚠️ Identify SEO issues (missing tags, duplicate headings, etc.)
📊 Generate structured SEO report
🕸️ Simple and extendable crawler architecture
🛠️ Tech Stack
Python 3.x
Requests
BeautifulSoup4
lxml (optional for faster parsing)
📦 Installation
1. Clone the repository
git clone https://github.com/saksham2132/Pythos_SEO_analyzer.git
cd Pythos_SEO_analyzer
2. Create virtual environment (recommended)
python -m venv venv

Activate it:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3. Install dependencies
pip install -r requirements.txt

If requirements.txt is missing, install manually:

pip install requests beautifulsoup4 lxml
▶️ Usage

Run the main script:

python main.py https://example.com

or (depending on your file structure):

python seo_analyzer.py https://example.com
📊 Example Output
🔎 Analyzing: https://example.com

Title: Example Domain
Meta Description: This domain is for use in illustrative examples...

✔ H1 Tags: 1 found
✔ H2 Tags: 3 found
⚠ Missing meta keywords
⚠ Low number of internal links

Score: 72/100
📁 Project Structure
Pythos_SEO_analyzer/
│
├── main.py              # Entry point
├── seo_analyzer.py     # Core crawler logic
├── utils.py            # Helper functions (if any)
├── requirements.txt    # Dependencies
└── README.md
⚙️ How It Works
User provides a URL
Script sends HTTP request using requests
HTML parsed using BeautifulSoup
SEO elements extracted:
Meta tags
Headings
Links
Rules applied to detect SEO issues
Final report generated
📌 SEO Checks Included
Missing <title> tag
Missing meta description
Multiple H1 tags
Broken/empty links
Poor heading hierarchy
Lack of internal linking
🔧 Future Improvements
🌐 Web dashboard using Flask/Django
📄 Export reports (PDF/CSV/JSON)
⚡ Multi-threaded crawling
📈 SEO scoring algorithm improvements
🧠 AI-based SEO suggestions
🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Saksham Sharma
GitHub: saksham2132