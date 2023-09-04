# Netflix Movies & TV Shows Recommender System
*This project is aimed at building a machine-learning model to recommend movies and TV shows to users based on their preferences and viewing history. The recommendation system utilizes collaborative filtering and content-based filtering techniques to provide personalized recommendations to users.*

### Dataset:
Kaggle -> [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Importing Dataframe**
```python
import pandas as pd

netflix = pd.read_csv('data/netflix_titles.csv')

print("Netflix Dataset: ", netflix.shape)
print("Data Columns: ", netflix.columns)
```

### Output:
```
Netflix Dataset:  (8807, 12)
Data Columns:  Index(['show_id', 'type', 'title', 'director', 'cast', 'country', 'date_added',
       'release_year', 'rating', 'duration', 'listed_in', 'description'],
      dtype='object')
```
