# API Movies

NodeJs

### Project Install

Clone the project :

    git clone https://github.com/Floriancrt/api-movies.git

#### Dependencies install
    
In the *root directory*, tape this command on your terminal :

    npm install <dependencies>
    
#### Launch application

Tape this command on your terminal to launch the application :

    nodemon start
    
The application will be launch at this url :

    http://localhost:3000/
    

### Routes

Generate movies files :

    GET /moviesFiles
   
Get all movies :

    GET /movies
   
Get one movie :

    GET /movie/:id
   
Create movie :

    POST /addmovie
    
    params = { title,director, date }
   
Delete movie :

    GET /deletemovie/:id
