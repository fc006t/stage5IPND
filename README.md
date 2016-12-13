## TO START THE UBUNTU SSH Session
* Go to https://console.cloud.google.com/home/dashboard?project=udacitystage5&utm_source=free-trial-2&utm_medium=email&utm_campaign=ft-welcome&utm_content=W1&pli=1
* Go to COMPUTE ENGINE
* Check off "ubuntu-trusty" and press "Start" if not already running
* After it starts press the "SSH" text under "Connect"
* An ubuntu shell will open



TO CONNECT TO TOURNAMENT TABLE THROUGH POSTGRES SQL ENGINE FROM SSH SHELL
sudo –s
sudo -u postgres psql postgres
/c tournament
/dt




## Synopsis

:sparkles: Final project containing  3 python files:

**fresh_tomatoes.py** - a prebuilt codebase used to format and display movie information to a webbrowser

**media.py** - my code to build a movie class to store movie informaton and provide a display method

**entertainment_center.py** - my code which contains the movie data, instantiates the movie objects and calls the movie display method

**fresh_tomatoes.html** - An output file created by running **entertainment_center.py** . This html file standalone without python at any time.



## Code Example
Movie objects are instantiated in **entertainment_center.py** as follows:

`godfather = media.Movie("The GodFather",
                        "A light hearted frolic into the lives of a hilarious Italian family",
                        "https://upload.wikimedia.org/wikipedia/en/1/1c/Godfather_ver1.jpg",
                        "https://www.youtube.com/watch?v=sY1S34973zA")
`                        
                        
Movie objects are displayed in "entertainment_center.py" as follows:

`fresh_tomatoes.open_movies_page(movies)                  
`

## Motivation

These python files were created to satisfy Stage 3, Final Project, IPND, Udacity

## Installation

* Install Python
* Create a directory for these files
* Unzip these files into that directory
* Start **entertainment_center.py**


## Contributors

Stood on the shoulders of **fresh_tomatoes.py** 

## MISC



(Github readme formatting guide: https://guides.github.com/features/mastering-markdown/)

