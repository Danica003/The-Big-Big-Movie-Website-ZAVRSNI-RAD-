If there's empty files, they're just placeholders, I will fill them as I do them
Done the sql part, i just made 2 different tables: movie and rating
Movie has everything basic: tmdb id, title, poster, and so on
And rating has a value and from what website it comes from
Both tables have a timestamp of when it was created, the ratings update it if there has been a change
There's also delete cascade in case there's a deleted movie it also deletes the ratings for it and there cannot be any ratings for nonexistent movies
And there cannot be multiple ratings from the same website for the same movie, so there's a unique foreign key to check that
Maybe I make an actor table? Actor director maybe so we can make an easy search for it :/
