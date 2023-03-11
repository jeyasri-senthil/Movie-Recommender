# ***Movie-Recommender***

*This movie recommender is a simple recommendation model that suggests movies based on user input. It uses content based filtering.*

## **About Dataset**

### **Dataset:** 
#### *<link 'https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset'>*
### **Context**
*These files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.
This dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.*

### **Content**
This dataset consists of the following files:

**movies_metadata.csv:** *The main Movies Metadata file. Contains information on 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies.*

**keywords.csv:** *Contains the movie plot keywords for our MovieLens movies. Available in the form of a stringified JSON Object.*

**credits.csv:** *Consists of Cast and Crew Information for all our movies. Available in the form of a stringified JSON Object.*

**links.csv:** *The file that contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.*

**links_small.csv:** *Contains the TMDB and IMDB IDs of a small subset of 9,000 movies of the Full Dataset.*

**ratings_small.csv:** *The subset of 100,000 ratings from 700 users on 9,000 movies.*

*The Full MovieLens Dataset consisting of 26 million ratings and 750,000 tag applications from 270,000 users on all the 45,000 movies in this dataset can be accessed here.*

### **Future Improvements**
*There are many ways to improve this movie recommender. One possible improvement is to use more advanced recommendation techniques, such as matrix factorization or deep learning. Another improvement could be to incorporate additional features, such as movie genres or release year, to make more targeted recommendations.*
