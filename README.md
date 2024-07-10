<p align="center">
  <h1 align="center">Movie-Recommender-System</h1>
</p>
<!-- ABOUT THE PROJECT -->
## About The Project

### Movie Recommender System

A movie recommendation system ,recommends movies of the similar content which you like to see, also give information about casts and user reviews on the movie you searched. Imagine the moment you ended your favorite movie and now you wish to see something similar to it?
But to find out about it you have to search all around the internet,so here's the solution for this. I have developed a website which will enable you to find out movies of your interests.

### How to use in your local machine

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
3. Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
4. Go to your browser and type http://127.0.0.1:5000/ in the address bar.
AND DONE!!!
Note:- if my api key is not working you can use yours by getting it from [https://www.themoviedb.org/](https://www.themoviedb.org/.)

### API KEY

I get my api key for movies from  <a href="https://www.themoviedb.org/settings/api">TMDB</a>

### Features
<ol>
  <li> Movie Overview 
      <ul>
        <li> Poster of your searched movie</li>
        <li> Some basics details about the movie with overview </li>
      </ul>
   </li>
  <li> Recommended Movies Section 
      <ul>
        <li> Autocomplete feature in search box</li>
        <li> suggestions list on searching </li>
        <li> TOP 10 similar movies </li>
        <li> "Click me" button on hovering on posters to research</li>
        <li> sorry note for the movies not in the database</li>
        <li> Autocomplete feature in search box</li>
        <li> suggestions list on searching </li>
      </ul>
   </li>
  <li> Casts section
      <ul>
        <li> You will get the information about top casts in the searched movie </li>
        <li> Character and Original name with photo of cast </li>
        <li> "know more" button will appear on hovering over the photo</li>
        <li> know more button will give you information about the cast birthdate and birthplace, biography</li>
      </ul>
   </li>
  <li> User Reviews section
    <ul>
        <li> some top fully explained comments or reviews on movie you searched </li>
        <li> sentifents with which the comments are written is attahed with comments with emojis</li>
      </ul>
  </li>
  <li> Completely a web-based Application: No need to install any application locally.
  </li>
</ol>

## Similarity Score

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

<!-- ROADMAP -->
## Resources Used

### Languages/Technologies
* CSS
* JavaScript
* HTML
* pycharm
* jupyter notebook
* heroku cli
### Framework
* Flask
## Sources of the datasets
1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)


## Notes
* Some movies are not available in the database so you will get results only from the list of 5000 movies

