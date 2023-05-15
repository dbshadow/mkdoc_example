# dmkdocs - Getting Started
---

## Prerequisites
---

Install `Docker` on your host

## Clone
---

```
$ git clone https://Hufflepuff@dev.azure.com/Hufflepuff/dmkdocs/_git/dmkdocs-getting-started
```

## Preview
---

```
$ cd dmkdocs-getting-started
$ docker run --rm -p 80:8000 -v "$(pwd)/src":/root/mkdocs/docs/src ctt828/dmkdocs
```

Open `http://ip:80` in your browser
