# pyseoa

🔎 **pyseo** is a fast, extensible Python library for analyzing SEO health across one or more URLs, with CLI support too. It performs audits for metadata, accessibility, structered data, performance scores, and more.

---

## 🚀 Features

- Analyze single or batch URLs
- Title, meta description, headers, alt tags
- Canonical links, Open Graph, Twitter tags
- Robots.txt, sitemap.xml, favicon check
- Accessibility (A11Y) hints
- Structured Data (JSON-LD)
- Lighthouse score via PageSpeedAPI (optional)
- Mobile-friendly detection
- Keyword density analysis (filter out of words possible)
- Export results to JSON, CSV, or HTML
- Export results to terminal
- Parallel processing with progress bar
- API and CLI ready

---

## 📦 Installation

```bash
pip install pyseoa
```

Or form source:
```bash
git clone https://github.com/sempre76/pyseoa.git
cd pyseoa
pip install -e
```

---

## 🧪 Usage

### Analyze a single URL
```
seo-analyze https://example.com
```

### Analyze multiple files from a file

```bash
seo-analyze -f urls.txt
```

### Full CLI Options

```bash
seo-analyze -h
```

---

## 📤 Output

- JSON report(s) in a folder (default: `seo_reports/`)
- Combined CSV summary (default: `seo_summary.csv`)
- Logs for any failed URLs in `seo_errors.log`

---

## 🛡 License
[MIT][LICENSE]

---

## 📫 Author

Created by Mario Semper
📧 mario.semper@masem.at

## 🔗 Links
- [PyPi](https://pypi.org/project/pyseoa/0.1.0/)
- [GitHub Repository](https://github.com/sempre76/pyseoa)

[![PyPI version](https://img.shields.io/pypi/v/pyseoa.svg)](https://pypi.org/project/pyseoa/)
[![Python versions](https://img.shields.io/pypi/pyversions/pyseoa.svg)](https://pypi.org/project/pyseoa/)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)




seo-analyze https://www.nike.com
seo-analyze https://example.com