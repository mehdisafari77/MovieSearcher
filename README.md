# MovieSearcher
A movie searching app using TMDB Api

## Summary
A movie searcher and database that connectd to th TMDB database in order to display popular movies, what's now playing and more. Follwoed aloong with a searchView where users can search their movies, see detailed views of those movies with their ratings, description, cast list, and even watch the trailers by connecting to YouTube. 

## Built With
* [SwiftUI](https://developer.apple.com/tutorials/swiftui)
* [UIKit](https://developer.apple.com/documentation/uikit)
* [TMDB-API](https://www.themoviedb.org/)

## Gif of App
![Gif](./MovieSearcher/Resources/Assets.xcassets/gif.dataset/gif1.gif)

## Installation Steps For Local Running
1. Clone project.
2. Open terminal
3. cd 'your-desired-path'
4. git clone 'paste-link-here'
5. open project in Xcode and run

## Code Snippet Of Order Model 
```swift
protocol MovieService {
    
    func fetchMovies(from endpoint: MovieListEndpoint, completion: @escaping (Result<MovieResponse, MovieError>) -> ())
    func fetchMovie(id: Int, completion: @escaping (Result<Movie, MovieError>) -> ())
    func searchMovie(query: String, completion: @escaping (Result<MovieResponse, MovieError>) -> ())
}
```


## Author

* **Mehdi Safari**

- [Link to Github](https://github.com/mehdisafari77)
- [Link to LinkedIn](https://www.linkedin.com/in/mehdi-safari-992799142/)
