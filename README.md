# dmkdocs - Getting Started
---

## Prerequisites
---

Install `Docker` on your host

## Clone
---

```
git clone https://github.com/dbshadow/mkdoc_example.git
```

## Preview
---

```
$ cd mkdoc_example
$ docker run --name docs --rm -p 80:8000 -v "$(pwd)/src":/root/mkdocs/docs/src dbshadow/dmkdocs
```

Open `http://ip:80` in your browser
