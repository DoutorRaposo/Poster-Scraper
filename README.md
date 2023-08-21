# Poster Scraper
#### Video Demo:  <URL HERE>
#### Description:
My final project is Poster Scraper: a website that shows all the posters for the movies of the artist of your choice: maybe a director, actor, producer or even more than one of those combined. 

You can search for an artist and if there is more than one result you can checkout a few titles that they are known for, a picture (if available, if not there's a placeholder) and the job that they are most known for. If there's only one result, you go directly to a page with the full bio, a pic and also all the types of jobs that they have been credited for (be it acting, directing, producing, etc.). You then select which ones you want to see and by pressing the button a gallery with all the posters will appear with a caption with title, synopsis about the movies and release date. If there's no poster for a title, instead of showing a placeholder, the title will not be exhibited at all.

In every page you can checkout the artist's profiles and mentioned titles, if you want, inside Poster Scraper itself or in the website supplier of the database: TMDB.

### Features:
- You can search and find all posters for a given artist and their jobs in a movie
- You can find a small biography plus a filmography list for every artist in the database
- You can find each movie individually and see everyone that's credited as cast or crew.
- You can query directly in the URL if you know the parameters. Everything is through "GET"


#### Personal thoughts:

- Positives: I made a few countermeasures in case of a wrong parameter of invalid value and the overall experience has been tested to avoid bugginess and is relatively responsive. Also, there is a great number of information you can get using only Poster Scraper.

- Negatives: I wish my frontend was more refined and my backend more robust, but they work well enough for user experience and in my next project I will study from everything I learned here to prepare beforehand and avoid rubberbanding, in frontend in particular.

### ABOUT MYSELF AND THE PROCESS: 
My name is Rafael de Andrade. I'm from Curitiba, Brazil. 

I started this project because I wanted to do a little web scraping by getting all the posters for a certain actor (to create a mosaic), then I thought I could expand to a web application.

This project helped me try out a lot of learned concepts from the classes. I found that TMDB have a free API for their database and I learned a lot using their documentation. I have a prototype only in Python using a library called Cinemagoer for IMDB and using Beautiful Soup for web scraping, then I evolved into a web app using the same tools. I found it very slow, but then I found out about TMDB's free API and recreated the whole thing to be faster and more user friendly. When it was functional, I did the frontend.