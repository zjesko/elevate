# FastAPI template

- Inspired by
  [fastapi-realworld-app](https://github.com/markqiu/fastapi-mongodb-realworld-example-app/)

## Installation

- Virtualenv:

```bash
pip3 install -r requirements.txt
```

- Docker:

```bash
docker pull akshatcx/fastapi-template:mongo
docker run -v $PWD/:/app -p 8080:8080 -d akshatcx/fastapi-template:mongo
```

OR

```bash
git clone /this/repo
docker build -t image:tag .
docker run -v $PWD/:/app -p 8080:8080 -d image:tag
```

