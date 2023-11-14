# journey-clustering

Reducing the Dimensions of the Customer Journey Dataset: This involves selecting the most relevant variables (like page URLs, time spent on each page, user clicks, etc.) and aggregating them into a simplified data structure. This step aims to reduce the size and complexity of the data while ensuring that the output aligns with the business objectives​​.

Creating Image-Like Representations of Customer Journeys: Here, a 3D embedding 'image' is created that combines all the data into a single structure. This involves representing touchpoints interacted with by customers in columns, the order of interactions in rows, and using a vector to describe the quality of each interaction​​.

Clustering Customer Journey "Images": In this step, data is cleaned and pre-processed, and dimensions are controlled to keep the number of variables manageable. Autoencoder neural networks are used to learn a semantic representation of the data, enabling dimension reduction and transformation of inputs into meaningful and compressed data​​.
