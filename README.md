# kinkybert
# Exploring Paraphilic and Normophilic Interests: Topic Modelling of Erotic Literature Subreddits Using BERTopic 
 Repository for the project submitted for MSc Psychological research methods with data science at the University of Sheffield 2024

# Overview 
This study investigates sexual interests, particularly paraphilic and normophilic behaviours, using data from erotic-focused subreddits on Reddit, an online platform with over 500 million users. By analyzing unfiltered, user-generated content, this research aims to provide insights into sexual behaviours that are not constrained by traditional clinical frameworks.

# Data Source 
The study initially sourced data from the Academic Torrents repository, specifically targeting 111 subreddits related to "kink," "BDSM," and "fetish." Due to computational limitations, a detailed preliminary analysis was conducted on the "KINK" subreddit. For the final analysis, four subreddits—Taboo Confessions, BDSMerotica, Erotica, and GoneWildStories—were selected, resulting in a dataset of 114,612 posts spanning from 2005 to 2023.

# Methodology
The study employed BERTopic, a state-of-the-art topic modelling technique, to extract latent themes from the textual data. Preprocessing involved cleaning and standardizing the text, including removing URLs, special characters, and common Reddit-specific terms. The "all-MiniLM-L6-v2" SentenceTransformer model was used to generate text embeddings, capturing the semantic meaning of the posts. 
