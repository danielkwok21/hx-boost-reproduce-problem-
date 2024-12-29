# what
A minimal reproducible example of my troubles with `hx-boost`.

# steps to reproduce
1. clone this repo
2. `go run main.go` to start server
3. open http://localhost:8080/ in browser
4. observe a video that is loaded, but not playing
5. click on "Back to home"

# expected
1. the entire page body be replaced with the same content as http://localhost:8080/

# observed
1. Even though the video in page isn't playing, there is a video being played in the background.
2. Open up console, and an error "Uncaught SyntaxError: redeclaration of let i" can be seen.