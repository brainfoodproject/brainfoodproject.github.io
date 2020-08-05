# Brain Food Project Web

### Dependencies
  - Go (http://golang.org/)
    - developed using v1.4
  - App Engine for Go (https://cloud.google.com/appengine/downloads)
    - developed using v1.9.23
  - Python 2.7 (https://www.python.org/downloads/release/python-2710/)

### To run

```sh
$ git clone https://github.com/nick11roberts/brain-food-project-web.git
$ cd brain-food-project-web
$ mkvirtualenv google --python=$(which python2.7)
$ dev_appserver.py app.yaml
```
and then visit [localhost:8080].

### To deploy

```sh
$ gcloud app deploy
```

[localhost:8080]: http://localhost:8080
