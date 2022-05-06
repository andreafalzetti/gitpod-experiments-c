# Gitpod Experiments C

Trying to answer: https://stackoverflow.com/questions/72066532/how-to-forward-ports-from-gitpod-container-to-local-machine-when-using-jetbrains

## How to use

```shell
docker build -t hello-world .
docker run -p 8080:80 hello-world
```
