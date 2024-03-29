# Go Project
### Where to Watch: Media Search Engine


Purpose
======
The purpose of this project was to make something using Go and the Go-Resty client. The project involved learning how to use Go, as well as several other libraries to support it. 

This project presents a simple search function, that allows you to search for a movie or TV show. It then calls the Utelly API which searches several streaming media pages, and returns a result of where you can watch that show. 

The Project
======
This is a simple two-page Go application that allows you to enter a search query on the main page, which then queries the [Utelly](link) API to find movies or tv shows that match that query, and displays which shows were found and where those movies or tv shows can be streamed online.

![screenshot of home page](src/homepage.png "Home Page")

![screenshot of results page](src/resultspage.png "Results Page")


References
======
### Project references
* [Resty](https://github.com/go-resty/resty)
* [Utelly API](https://market.mashape.com/utelly/utelly)
* [Mux](https://github.com/gorilla/mux)
* [Consuming JSON APIs with Go](https://medium.com/@IndianGuru/consuming-json-apis-with-go-d711efc1dcf9)
* [Building a RESTful API with Golang](https://www.codementor.io/codehakase/building-a-restful-api-with-golang-a6yivzqdo)
* [GoWebTemplates](https://gowebexamples.com/templates/)
### Learning Go
##### Pluralsight
* [Creating Web Applications with Go](https://app.pluralsight.com/library/courses/creating-web-applications-go-update/table-of-contents)
* [Code School: On Track with Golang](https://app.pluralsight.com/library/courses/code-school-on-track-with-golang/table-of-contents)
* [Go: Getting Started](https://app.pluralsight.com/library/courses/go-getting-started/table-of-contents)
##### YouTube Tutorials
* [Create A Simple RESTful API With Golang](https://www.youtube.com/watch?v=t96hBT53S4U)


Future Iterations
======
Future items I would like to tackle on this project include:
* Figure out how to get the CSS file to work so that all of the in-line styles can disappear (I'm sorry, I know they're gross...)
* A log in and rating feature for movies/tv shows
* A "watch list" for movies or tv shows that people recommend
* Potential social integration for other people to see what movies you watched recently
