# Hello Go Project

This is a simple [Hello](https://go.dev/doc/tutorial/getting-started) Go project that prints a quote using the `rsc.io/quote` package.<br>


## Project Structure
`go.mod` Module file defining the module path and dependencies.<br>
`go.sum` Checksum file that ensures the integrity of the dependencies.<br>
`hello.go` Source file that prints a quote from the quotes.Go() func.<br>

## Prerequisites
- Go 1.23 or later

## Getting Started

1. Clone the repository:

    ```sh
    git clone https://github.com/feed0/hello-go.git
    cd hello-go
    ```

2. Download the dependencies:

    ```sh
    go mod tidy
    ```

3. Run the application:

    ```sh
    go run .
    ```
