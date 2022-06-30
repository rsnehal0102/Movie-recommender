# Movie-recommender
- A recommender system based on content based filtering that has been deployed using various machine learning algorithms such as the cosine simalirity algorithm.
- It is using a data set with more than 4000 movies with more than 10 parameters each.
- Feature extraction has also been used to get numerical values associated.

## Sample of the data set
![1](https://user-images.githubusercontent.com/103516326/176668057-03cecf5d-6efd-4e9f-beab-80628f29169c.jpg)

## User input for favourite movie
In order to find the closest movie in the dataset to that given by the user we have used difflib library.
![2](https://user-images.githubusercontent.com/103516326/176668341-03ba2070-59cb-45c4-88fb-9203778f6bc2.jpg)

## Finding the most similar movie according to the given parameters
- The chosen parameters in this case were to obtain best yield were: 
    - Genres
    - keywords
    - overview
    - cast
    - director
- Next we used the cosine simalirirty algorithm to obtain the list of 10 most similar movies
![3](https://user-images.githubusercontent.com/103516326/176668354-438396ef-70fc-4c3c-a186-e672f320b1a3.jpg)

