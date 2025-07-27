# Movie Covers (2001-2010)
Movie covers from the 2000's (2001-2010).

## ID
Use the IMDb movie ID without the initial "tt". For greater compability in future, remove left zeros (0121765 -> 121765).

## How to use links
Use this URL pattern for default covers (you'll have to implement the automation yourself):
```python
    https://raw.githubusercontent.com/st-alves/movie-covers-${decade}/refs/heads/main/${type}/${movie_id}.jpg"
```

Example: 
<br>```https://raw.githubusercontent.com/st-alves/movie-covers-2000/refs/heads/main/letterboxd/121765.jpg```

Only "letterboxd" is available for ```${type}``` for now.

### Images sizes
Letterboxd: 350 x 525 px

### Main Project
[Movie Covers](https://github.com/st-alves/movie-covers)
