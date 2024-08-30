## Amazon Alexa Skill for IMDB Interaction

This repository contains the code for an Amazon Alexa Skill that enables users to interact with movie data from IMDB through voice commands. The skill allows users to retrieve various pieces of information, such as movie ratings, director names, durations, synopses, and similar films.

### Key Features:
- **Voice-Activated Movie Information**: Users can ask Alexa for specific details about movies, including ratings, director names, durations, and more.
- **IMDB Web Scraping**: The skill scrapes data directly from the IMDB website, ensuring that users receive the most up-to-date information.
- **Custom Intents**: In addition to built-in intents, this skill includes custom intents for handling specific user queries about movies.
- **AWS Lambda Integration**: The backend code is deployed on AWS Lambda, making the skill serverless and scalable.

### How It Works:
- **Alexa Skill**: Users interact with the skill through voice commands, triggering specific intents.
- **IMDB Scraper**: The skill scrapes the required movie data from the IMDB website in real-time.
- **Response Generation**: The scraped data is processed and returned to the user in a natural language format.
