# Code-Crafters-News-Aggregator
Features
1. News Aggregation
Fetches news from verified local sources using the NewsData.io API.
Ensures timely updates of local news.
2. Content Categorization
Categories include:
Top News
Sports
Business
Technology
World
Politics
Entertainment
3. Personalized News Feeds
Allows users to select preferred categories.
Displays tailored content based on user preferences.
4. Information Accuracy
Aggregates only from trusted and verified sources.
Provides fallback mechanisms for missing or incomplete data.

Tech Stack
Frontend: HTML, CSS, JavaScript
API: NewsData.io API
Backend: JavaScript (fetch API for API calls)

Installation and Setup
Clone the repository: git clone https://github.com/HaneeshaBasam/code-crafters-news-aggregator.git
Navigate to the project directory: cd code-crafters-news-aggregator
Obtain an API key from NewsData.io and replace YOUR_API_KEY in the script.js file.
Open the index.html file in your browser to view the application.

Project Structure
news-aggregator/
├── index.html          # Main HTML file
├── styles.css          # Styling for the application
├── script.js           # JavaScript logic
├── assets/             # Images and icons
└── README.md           # Project documentation

How It Works
The application fetches news data using the NewsData.io API.
News articles are categorized into predefined sections (e.g., Sports, Technology).
The user interface dynamically displays news in cards with images, titles, and links to full articles.
Users can navigate through categories to view specific news sections.

Future Enhancements
Add user authentication for personalized settings.
Implement search functionality for specific news topics.
Enable offline viewing using caching.
Integrate additional APIs for broader coverage.

Contribution Guidelines
Fork the repository.
Create a new branch for your feature or bug fix: git checkout -b feature-name
Commit your changes: git commit -m "Add feature-name"
Push to your branch: git push origin feature-name
Open a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
NewsData.io API for providing reliable news data.
Open-source libraries and frameworks for simplifying development.
