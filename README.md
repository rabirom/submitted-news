# Submitted News

**An AI-powered news platform for discovering and publishing news from across the world.**

🌐 **Live Website:** https://aliceblue-antelope-926456.hostingersite.com/

## About the Project

Submitted News is a news website designed to aggregate and publish news from multiple sources. The project uses automation to process news feeds and publish articles through WordPress.

## Features

- Automated news collection from RSS feeds.
- Python-based news processing and publishing workflow.
- WordPress integration for publishing articles.
- Configurable news sources.
- Website powered by WordPress.

## Technology Stack

- **CMS:** WordPress
- **Language:** Python
- **Data Sources:** RSS feeds
- **Publishing:** WordPress REST API

## Project Structure

```text
submitted-news/
├── news_engine.py       # News processing and publishing automation
├── feeds.json            # Configured RSS feed sources
├── requirements.txt      # Python dependencies
├── .gitignore            # Excluded files and secrets
└── README.md             # Project documentation
```

## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/submitted-news.git
   cd submitted-news
   ```

2. Install the required Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure the required environment variables for your WordPress connection and any AI services used by the publishing engine.

4. Review `feeds.json` to configure the news sources.

5. Run the publishing script according to your environment's configuration:

   ```bash
   python news_engine.py
   ```

**Note:** Configure credentials securely before running the script. Do not commit API keys, passwords, or private environment files to GitHub.

## Live Website

Visit [Submitted News](https://aliceblue-antelope-926456.hostingersite.com/) to explore the published website.

## Purpose

This repository documents the source code and automation supporting Submitted News. The live WordPress website, its database, media library, and server configuration may be maintained separately from this repository.

## License

No license has been specified yet. All rights remain with their respective owners unless a license is added.
