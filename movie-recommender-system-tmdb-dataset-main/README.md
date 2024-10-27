# Movie Recommender System

## Abstract
In recent years, personalized recommendation systems have become essential for streaming platforms, helping users discover content that aligns with their preferences. This project presents a **Movie Recommender System** built using **Streamlit** for the frontend, with **CountVectorizer** to generate recommendations based on text similarity. The system aims to provide users with a straightforward, interactive interface for finding movies similar to those they enjoy.

## Introduction
With the ever-growing amount of content available online, users often struggle to find movies that match their tastes. Recommender systems alleviate this problem by suggesting content that aligns with user interests. This project leverages **natural language processing (NLP)** techniques, using **CountVectorizer** to calculate the similarity between movie descriptions, genres, and other textual metadata.

By integrating Streamlit as the front end, this recommender system offers an accessible, interactive platform for users to explore movie recommendations. Users can search for movies, view similar titles, and interact with a clean, visually appealing interface.

### Key Features
- **Interactive Frontend**: Built with Streamlit, providing an intuitive interface.
- **Content-Based Filtering**: Uses CountVectorizer to find movies with similar textual metadata.
- **Image Display**: Movie posters and images are displayed alongside recommendations for enhanced user experience.
  
## Technology Stack
- **Frontend**: Streamlit
- **Backend/Recommendation Engine**: Python, CountVectorizer
- **Data**: Movie metadata including genres, summaries, etc.

## Run the application:
- **streamlit run app.py**

