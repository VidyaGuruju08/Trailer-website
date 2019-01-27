# Trailer website

A Python program that produces the HTML for a movie website that displays a number of movies. Click on a movie poster to play its trailer.

Python is required to run this project. The Python executable should be in your default path, which the Python installer should have set.

 ## Project contents ##
This project consists for the following files:

entertainment_center.py - main Python script to run
media.py - contains the class Movie that stores movie details
fresh_tomatoes.py - creates the HTML file for the website

## Documentation ##
Movie object class
The Movie object class consists of four class variables, a simple constructor method, and a class method for playing a Movie object's movie trailer. The code is located in media.py.

constructor method
The constructor method is called when a new Movie object is created and must include four arguments -- title, year, poster_url, and trailer_url. Each of these arguments is discussed further below.

movie.title
movie.title is string the specifies the the title of rhe movie.

movie.poster_image
movie.poster_image is a string containing a URL linking to an image which will be used to represent the Movie object, such as a movie poster or DVD box cover. The movie trailer page portion of this project displays these images.

movie.trailer_youtube_url
movie.trailer_youtube_url is a string containing a URL linking to the movie trailer on YouTube.com. The movie trailer page portion of the this project extracts the YouTube id from the URL, so while links to other video services are valid in the Movie class object, they will not work with the movie trailers page.

show_trailer method
show_trailer can be called on any Movie class object to launch that object's movie trailer in a webpage. This method is useful for testing but is not used by the script that generates the finished movie trailers page.


## To Run the project: ##
python entertainment_center.py
Your default browser should launch a new tab displaying the movie trailer website.


