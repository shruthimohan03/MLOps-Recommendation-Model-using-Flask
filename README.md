# MACHINE LEARNING MODEL: Login page and model building using flask 

MODEL: SERIES RECOMMENDATION SYSTEM (rsmodel.py)
Dataset: TV series

DESCRIPTION:
-This project is a recommendation system for TV series built using Flask and the concept of cosine similarity. It consists of two main components: a login page and a model for series recommendations.

-The login page provides authentication for users to access the recommendation system securely. Once authenticated, users can utilize the search bar functionality to input the name of a TV series they are interested in.

-Behind the scenes, the recommendation model (implemented in rsmodel.py) leverages cosine similarity to calculate the similarity between the input series and other series in the dataset. Cosine similarity is a metric used to determine how similar two series are based on their features or attributes.

-Upon receiving the input series name, the model computes the cosine similarity between the input series and all other series in the dataset. Then, it returns the top 10 series that are most similar to the input series. These recommended series are displayed to the user, providing them with options for further viewing based on their initial interest.

Overall, this project aims to enhance the user experience by providing personalized recommendations for TV series, helping users discover new content that aligns with their preferences.
