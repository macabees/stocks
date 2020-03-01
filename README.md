# Stocks
Displays stock price and company details.

## Stocks (Project Info)
[Website](https://github.com/alexanderepstein/Bash-Snippets)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/stocks/)

## Build image
`$ docker build -t macabees/stocks:latest .`

## Run image
Display Stock Information
`$ docker run -it --rm macabees/stocks GOOG`

Display Company Information
`$ docker run -it --rm macabees/stocks apple`

## Docker Push
`$ docker push -t macabees/stocks:latest`

Note: requires `docker login`

## Help
`$ docker run -it --rm macabees/stocks help`
