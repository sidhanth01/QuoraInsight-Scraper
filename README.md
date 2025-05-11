# QuoraInsight-Scraper

QuoraInsight Scrapper is a Python-based command-line tool that extracts public profile insights from Quora using Selenium. It retrieves information such as name, profession, profile image, bio, number of answers, questions, posts, followers, and following count.

## 🚀 Features

- Headless browser automation using Chrome or Firefox
- Fake user-agent headers to reduce blocking
- Extracts
  - Name
  - Profession
  - Bio
  - Profile image URL
  - Answers, questions, shares, and posts count
  - Followers and following count

## 🛠️ Requirements

- Python 3.7+
- Google Chrome or Mozilla Firefox installed
- pip (Python package installer)

## 📦 Installation

1. Clone the repository

2. Install dependencies:  pip install -r requirements.txt

3. Usage:   python quora_scraper.py <quora_username> --browser <chrome|firefox>

## Output

If --browser is not specified, Chrome will be used by default.

- Example : python quora_scraper.py Adam-Dangelo --browser chrome

   The script prints a JSON-formatted string containing the extracted profile data :


  "name": "Adam D'Angelo",
  "profession": "CEO at Quora",
  "profile_image": "https://qph.fs.quoracdn.net/main-thumb...",
  "bio": "Founder of Quora and former CTO of Facebook...",
  "answers_count": "320",
  "questions_count": "15",
  "shares": "100",
  "posts": "30",
  "followers": "500K",
  "following": "10"


---

⚠️ Disclaimer

This tool scrapes publicly available information (Educational purpose only). Respect Quora’s terms of service when using it.

May break if Quora updates their layout or structure.





