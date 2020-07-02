 
# Hello <s>World</s> Full Cycle

	package main
	import "fmt"

	func main() {

	    fmt.Println("Hello Full Cycle")

	}

# Build

	docker build . -t go-hello-full-cycle


# Run

	docker run -it go-hello-full-cycle

# Run from Docker Hub

	docker run 360guilherme/go-hello-full-cycle
