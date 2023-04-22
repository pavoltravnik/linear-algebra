# linear-algebra

## Build custom image

Install dependencies

bash```
docker pull jupyter/scipy-notebook:latest
docker build -t jupyter/scipy-notebook-custom docker
```


## Run customised jupyter docker image

bash```
docker run -it --rm -p 8888:8888 -v "${PWD}/notebooks":/home/jovyan jupyter/scipy-notebook-custom
```