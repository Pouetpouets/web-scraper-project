# Web Scraper Project

A robust web scraping project built with Python, using BeautifulSoup4 and requests libraries.

## Features

- Robust error handling
- Random User-Agent rotation
- Rate limiting and respect for robots.txt
- Data export to CSV
- Configurable settings

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Pouetpouets/web-scraper-project.git
cd web-scraper-project
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a .env file with your configuration:
```bash
cp .env.example .env
# Edit .env with your settings
```

## Usage

Run the scraper:
```bash
python src/scraper.py
```

## Project Structure

```
├── src/
│   ├── scraper.py       # Main scraper module
│   └── utils/           # Utility functions
├── data/                # Scraped data storage
├── requirements.txt     # Project dependencies
├── .env                 # Configuration file
└── README.md           # Project documentation
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.