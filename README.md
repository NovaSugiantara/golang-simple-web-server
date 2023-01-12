This project is a simple web server created using the Go programming language. It demonstrates the use of various features such as dynamic routing, middleware, logging, serving static content, serving content from a directory and serving content through HTTPS.

The project uses the "github.com/gorilla/mux" package for dynamic routing, which allows for multiple routes to handle different requests. It also uses the "github.com/urfave/negroni" package for middleware and logging, which allows for the addition of various middleware handlers to the server, such as logging.

The project also demonstrates serving static content and content from a directory using the "net/http" package's http.FileServer() function. Additionally, it demonstrates serving content through HTTPS using the http.ListenAndServeTLS() function and providing SSL/TLS certificate files.

The project also uses package "github.com/joho/godotenv" to read .env file which contains the configuration of the server.

To run the project, simply run the command "go run [filename].go" in the command line and then access the server via "https://localhost:port" in a browser.

In conclusion, this project is a simple web server that demonstrates the use of various features in Go such as dynamic routing, middleware, logging, serving static content, serving content from a directory and serving content through HTTPS. It can be used as a starting point for building more complex web applications.
