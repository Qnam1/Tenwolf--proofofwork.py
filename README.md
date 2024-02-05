# TenWolf

TenWolf is a news aggregator that fetches trending news articles and allows users to rate, provide feedback, sponsor articles, and add advertising content. The platform aims to provide users with a personalized news experience and create engagement with the content.

## Features

1. Fetch Trending News: The platform fetches trending news articles from various categories such as technology, science, business, and world news.

2. Rate and Provide Feedback: Users can rate news articles on a scale of 1 to 5 and provide feedback on the content.

3. Sponsor Articles: Users have the option to sponsor articles by adding sponsored content to the platform.

4. Add Advertising Content: Users can add advertising content to news articles to promote products or services.

5. Generate Unique Token: TenWolf generates a unique token for each user to track their interactions with the platform.

## How to Use

1. Fetch Trending News: Use the `fetch_trending_news` function with your News API key to fetch trending news articles.

2. Rate and Provide Feedback: After fetching news articles, users can rate articles and provide feedback.

3. Sponsor Articles: Users can choose to sponsor articles by adding sponsored content with the `add_sponsor_content` function.

4. Add Advertising Content: Users can add advertising content to articles using the `add_advertising_content` function.

5. Generate Unique Token: TenWolf generates a unique token for each user for tracking their interactions.

## Dependencies

- `requests`: To make API requests to fetch news articles.
- `random`: To generate random tokens for users.
- `json`: To work with JSON data.
- `pathlib`: To manage file paths and directories.
- `hashlib`: To hash URLs of news articles for uniqueness.

## Getting Started

1. Create a News API key from [News API](https://newsapi.org/).
2. Update the `api_key` variable with your News API key.
3. Run the script to fetch trending news, rate articles, provide feedback, and interact with articles.

## Contributing

Contributions to improve and enhance TenWolf are welcome! Feel free to fork the repository, make changes, and submit a pull request.

---

Thank you for using TenWolf! We hope you enjoy a personalized news experience with our platform. 💡

[![CodeFactor](https://www.codefactor.io/repository/github/qnam1/tenwolf-swen.py/badge)](https://www.codefactor.io/repository/github/qnam1/tenwolf-swen.py)
