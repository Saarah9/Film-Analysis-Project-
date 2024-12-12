# Film-Analysis-Project-
This project involves analyzing a dataset of films to perform various tasks such as statistical computations, data visualizations, and deriving insights. 
## Dataset  
The dataset used is sourced from IMDb and contains metadata about movies. It is loaded directly from the following URL:  
[https://raw.githubusercontent.com/Godoy/imdb-5000-movie-dataset/master/data/movie_metadata.csv](https://raw.githubusercontent.com/Godoy/imdb-5000-movie-dataset/master/data/movie_metadata.csv)  

## Tasks  
### Load the Data  
- Load the dataset into a `pandas` DataFrame.  

### Calculate Observations  
- Calculate and print the total number of observations in the dataset.  

### Frequency Table  
- Extract the frequency table for the `content_rating` column.  

### Bar Chart  
- Create a bar chart showing the top 5 content ratings by frequency in descending order.  

### Histogram  
- Create a histogram displaying the distribution of film durations.  

### IMDb Scores by Film Categories  
- Calculate the mean IMDb scores for films categorized as "color" and "black & white."  

### Film Duration Statistics  
- Compute the mean, minimum, and maximum durations of films.  

### Unique Genres  
- Calculate the total number of unique genres in the dataset.  

### Scatterplot  
- Create a scatterplot with:  
  - `x-axis`: Duration of the film.  
  - `y-axis`: IMDb score.  
  - `hue`: Color differentiation (Color vs. Black & White).  

### Actor Frequency Table  
- Identify the top 5 actors in the Action genre based on combined frequency from three actor columns.  

## Libraries Used  
- `pandas`  
- `matplotlib`  
- `seaborn`  


## How to Run  
1. Ensure `pandas`, `matplotlib`, and `seaborn` are installed.  
   ```bash  
   pip install pandas matplotlib seaborn 
