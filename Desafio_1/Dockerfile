FROM golang:1.12-alpine

# Set the Current Working Directory inside the container
WORKDIR /app/hello_full_cycle

COPY . .

# Build the Go app
RUN go build -o ./out/hello_full_cycle .


# Run the binary program produced by `go install`
CMD ["./out/hello_full_cycle"]