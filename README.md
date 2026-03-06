# 🚀 GSoC 2026 Organization Explorer

[![GSoC 2026](https://img.shields.io/badge/GSoC-2026-orange.svg)](https://summerofcode.withgoogle.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Code Style: Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

**The ultimate CLI companion for Google Summer of Code 2026 contributors.** Stop scrolling through endless web pages and find your perfect organization directly from your terminal.

## ✨ Features

- 🏎️ **Blazing Fast**: Smart local caching for instant results.
- 🔍 **Deep Search**: Find organizations by name, technology, or mission statement.
- 🛠️ **Advanced Filtering**: Combine multiple technologies and categories to narrow down your search.
- 📊 **Analytics**: View statistics on the most popular technologies in GSoC 2026.
- 📖 **Complete Dossiers**: Detailed view of project ideas, source code, and guidance links.
- 🎨 **Beautiful UI**: High-fidelity terminal output powered by `rich`.

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/UnsettledAverage73/gsoc-2026-explorer.git
cd gsoc-2026-explorer

# Install dependencies
pip install -r requirements.txt

# Make the tool executable
chmod +x gsoc-2026
```

## 🚀 Usage

### List & Filter
```bash
# List top 50 organizations
./gsoc-2026 list

# Find organizations using BOTH Python and React
./gsoc-2026 list --tech python --tech reactjs

# Sort by organizations with the most technologies
./gsoc-2026 list --sort tech_count
```

### Search & Explore
```bash
# Search for anything related to "machine learning"
./gsoc-2026 search "machine learning"

# Get full details for an organization using its slug
./gsoc-2026 info openmrs
```

### Insights
```bash
# View trending technologies for GSoC 2026
./gsoc-2026 stats
```

## 🛠️ Tech Stack

- [Rich](https://github.com/Textualize/rich) - For the beautiful terminal UI.
- [Click](https://click.palletsprojects.com/) - For a robust CLI interface.
- [Requests](https://requests.readthedocs.io/) - For seamless API integration.

## 🤝 Contributing

Contributions are welcome! Whether it's a bug fix, a new feature, or improving documentation, feel free to open a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Disclaimer: This tool is not officially affiliated with Google Summer of Code.*
