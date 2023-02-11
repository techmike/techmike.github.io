# Techmike Blog Build

## Build

```bash

docker build -t techmike-blog .
```


## Run
```bash
docker run -it --rm --name techmike-github-blog -v "$PWD":/techmike -p 4000:4000 techmike-blog bash
```