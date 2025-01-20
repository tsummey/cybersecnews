# Cybersecurity News #

To run: 'python -m streamlit run .\rss.py'

## Key Features

### 1. **Automated RSS Feed Aggregation**
   - Fetches articles from reputable cybersecurity sources such as:
     - Krebs on Security
     - BleepingComputer
     - Dark Reading
     - The Hacker News
     - Palo Alto's Unit 42, and more.
   - Monitors for new articles daily and ensures the feed is always current.

### 2. **Keyword-Based Filtering**
   - Utilizes a comprehensive list of cybersecurity-related keywords (e.g., APT, ransomware, zero-day, IoT security) to extract only the most relevant articles.
   - Ensures you get focused insights rather than a flood of irrelevant news.

### 3. **Interactive Streamlit Dashboard**
   - Displays articles in an organized and visually appealing layout.
   - Key features include:
     - Article titles, summaries, and publication dates.
     - Links to the full articles for further reading.
     - A responsive interface with customizable article views.

### 4. **Duplicate and Outdated Content Removal**
   - Detects and eliminates duplicate entries to maintain a clean data set.
   - Ensures articles displayed are within the last 30 days.

### 5. **JSON Data Storage**
   - Saves processed articles in a JSON file (`cybersecnews.json`) for reuse and offline access.
   - Automatically refreshes outdated JSON data.

### 6. **Built-in Error Handling and Logging**
   - Logs errors and ensures stable performance, even during network issues or malformed RSS feeds.

### 7. **Extensibility and Modularity**
   - Easily add new RSS sources or modify the keyword list to tailor the app to your needs.
   - The modular design simplifies updates and maintenance.
