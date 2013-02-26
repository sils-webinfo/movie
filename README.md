#movie#

##movie resources##
- The list of movies ordered alphabetically by their names
- The list of actors appeared in the movies
- The list of genres
- The list of directors
- The list of countries
- The list of languages
- A single movie
- A list of movies that match some search criteria.

##ID attribute values##
- *movies*- Applied to a DIV tag. The list of movies in this representation. This list may contian only one movie.
- *actors*- Applied to a DIV tag. The list of actors in this representation. 
- *genres*- Applied to a DIV tag. The list of genres in this representation.
- *directors*- Applied to a DIV tag. The list of directors in this representation.
- *countries*- Applied to a DIV tag. The list of countries in this representation.
- *languages*- Applied to a DIV tag. The list of languages in this representation.

##Class attribute values##

- *all*- Applied to a UL tag. When this element is a descendant of DIV.id="movies" it may have one or more LI.class="movie" descendant elements. When this element is a descendant of DIV.id="actors" it may have one or more LI.class="actor" descendant elements. When this element is a descendant of DIV.id="genres" it may have one or more LI.class="genre" descendant elements. When this element is a descendant of DIV.id="directors" it may have one or more LI.class="movie" descendant elements. When this element is a descendant of DIV.id="countris" it may have one or more LI.class="country" descendant elements. When this element is a descendant of DIV.id="languages" it may have one or more LI.class="language" descendant elements.
- *movie*- Applied to a LI tag. This gives the outbound link to link a specific movie.
- *actor*- Applied to a LI tag. This gives the outbound link to link a list of movies which are acted by a specific actor.
- *genre*- Applied to a LI tag. This gives the outbound link to link a list of movies which belongs to a specific genre.
- *director*- Applied to a LI tag. This gives the outbound link to link a list of movies which directed by a specific directors.
- *country*- Applied to a LI tag. This gives the outbound link to link a list of movies which come from a specific country.
- *language*- Applied to a LI tag. This gives the outbound link to link a list of movies which use a specific language.
- *actor-movies*- Applied to a UL tag. A list of moives which are acted by a specific actor.
- *genre-movies*- Applied to a UL tag. A list of moives which belong to a specifc genre.
- *diector-movies*- Applied to a UL tag. A list of moives which are directed by a specific director.
- *country-movies*- Applied to a UL tag. A list of moives which come from a specific country.
- *language-movies*- Applied to a UL tag. A list of moives which use a specific language.
- *search-movies*- Applied to a UL tag. A list of moives which match some search criteria.
- *single-movie*- Applied to a UL tag. A representation of a single message. This element is a descendant of DIV.id="movies". 
- *movie-content*- Applied to a LI tag. This element is a descendant of UL.class="single-movie". It contains descendant elements like SPAN.class="movie-name" which give some descriptions.  
- *movie-video*- Applied to a FORM tag. A representation of a movie`s video.
- *movie-name*- Applied to a SPAN tag. This gives the name of a movie.
- *movie-actors*- Applied to a SPAN tag. This gives the actors of the movie.
- *movie-genres*- Applied to a SPAN tag. This gives the genres of the movie.
- *movie-directors*- Applied to a SPAN tag. This gives the directors of the movie.
- *movie-countries*- Applied to a SPAN tag. This gives the countries of the movie.
- *movie-languages*- Applied to a SPAN tag. This gives the languages of the movie.
- *movie-add*- Applied to a FORM tag. A non-idempotent link to create a new movie.
- *movie-update*- Applied to a FORM tag. A non-idempotent link to update an existing movie. 
- *movie-search*- Applied to a FORM tag. A templated query link to search movies that match some search criteria.



##Name attribute values##

##Rel attribute values##

- *movie*- Applied to an A tag. A reference to the movie representation.
- *all-movie*- Applied to an A tag. A reference to the starting URI for the application.
- *all-actors*- Applied to an A tag. A reference to the list of actors.
- *all-genres*- Applied to an A tag. A reference to the list of genres.
- *all-directors*- Applied to an A tag. A reference to the list of directors.
- *all-countries*- Applied to an A tag. A reference to the list of countries.
- *all-language*- Applied to an A tag. A reference to the list of languages.
- *actor-movies*- Applied to an A tag. A reference to the list of movies which are acted by a specific actor.
- *genre-movies*- Applied to an A tag. A reference to the list of movies which belong to a specific genre. 
- *director-movies*- Applied to an A tag. A reference to the list of movies which are directed by a specific director. 
- *country-movies*- Applied to an A tag. A reference to the list of movies which come from a specific country. 
- *language-movies*- Applied to an A tag. A reference to the list of movies which use a specific language. 
- *movie-video*- Applied to an A tag. A reference to the movie`s video.
- *movie-add*- Applied to an A tag. A reference to the movie-add FORM.
- *movie-update*- Applied to an A tag. A reference to the movie-update FORM.
- *movie-search*- Applied to an A tag. A reference to the movie-search FORM.
