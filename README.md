# Cinema Correlation Analysis
![Why-is-Popcorn-a-Movie-Food](https://github.com/jeanbaptistejacq/Cinema-Correlation-Analysis/assets/80902643/237bb8eb-553b-46ce-862f-bf1e4e455fa8)
</br>
</br>
We conduct exploratory Data analysis and Data cleaning of a movie dataset. The primary goal is to analyze the dataset and uncover correlations between various attributes, with a focus on exploring the relationships between budget, gross revenue, movie production companies, and viewer votes.

## Content

[1. Getting Started](#getting-started)  
[2. Data Source](#data-source)  
[3. Correlation Analysis](#correlation-analysis)  
[4. License](#license)  

## Getting Started
<ol>
  <li>Fork this repository</li>
  <li>Clone the repository to your local computer</li>
  <li>Open the downloaded ipynb file using Jupyter notebook</li>
  <li>You can now run the project</li>
</ol>


## Data Source

The dataset is taken from Kaggle and named 'movies.csv' in the repository. The dataset contains the information about movies including their company, budget and votes received, dates and many other.

## Correlation Analysis

The central objective of this project was to identify correlations between the following variables:

- Budget and Gross Revenue: Assessing whether there exists a correlation between the budget invested in a movie and its gross revenue.
- Gross Revenue and Production Company: Investigating whether the production company influences the gross revenue of a movie.
- Gross Revenue and Viewer Votes: Exploring the relationship between viewer votes and the gross revenue of a movie.
</br>
We are currently facing an issue: 28% of the data for the budget variable is missing. To address this, we have decided to impute the missing values using predictions from a linear regression model. We will split the dataset into training and test sets, then use the model to predict the missing values.

</br>
</br>


<img width="700" alt="chartmovie" src="https://github.com/jeanbaptistejacq/Cinema-Correlation-Analysis/assets/80902643/83cea413-a5eb-4989-8767-614c9d92dee6"></br>


![correlation](https://github.com/jeanbaptistejacq/Cinema-Correlation-Analysis/assets/80902643/8c7bceb8-e20d-466d-a992-b4941d348066)
</br>


![corr](https://github.com/jeanbaptistejacq/Cinema-Correlation-Analysis/assets/80902643/a96c5140-56f9-414c-bebd-943acf40754e)
</br>

The analysis of the dataset showed that the budget and votes have a high correlation with the gross revenue of the movie.
</br>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
