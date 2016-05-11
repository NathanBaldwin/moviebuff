# Movie Buff App

Completed as a group project (team of 3) at Nashville Software School, Movie Buff allows users to create an account, find movies (via the imdb movie api), add movies to their own collection, search their movie collection, mark movies as 'watched', rate 'watched' movies on scale of 1-10, and filter 'watched' movies by rating.

## How It Works

#### Create an Account

Visit www.onlinemoviecollection.com to create an account.

Important note: THIS APP IS NOT SECURE. Please use a fake email address and password to register.

#### Search for Movies

Once logged in, use the search bar in the top left corner to find any movie contained in the IMDB database. Enter the title of the movie you wish to find, and hit 'enter'. Any movie title in the IMDB database containing the word(s) in your search criteria will be returned. For instance, if you search 'jaws', all movies containing the word 'jaws' in the title will be returned.

Movies that have already been added to your collection will also apear if they match your search criteria. Movies in your collection will have a 'Watched' button (rather than an 'add' buttun) underneath, or, if you've already ranked the movie, you will see your specified ranking.

Click the 'Add' button to add any movie your collection.

#### Navigation Options

Use the navigation options in the upper left corner to view all your movies in your collection, only 'unwatched' movies, or only the movies you've designated as 'watched'.

#### Rate Movies

Once you have added a movie to your collection and clicked the 'Watched' button underneath it, you will be able to rank that movie on a scale of 1-10.


#### Filter by Ranking

While on the 'All' or 'Watched' pages, you can use the slider to filter any movies you have already ranked.


## Technologies Used

This project served as an exercise to become more comfortable using jQuery, Bootstrap, Handlebars, Lodash, Firebase, and making API calls.

We used Requrire.js heavily in order to practice writing modular code.

I also deployed this app via DigitalOcean using NGINX
