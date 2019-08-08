# Dim Sum Image Classification App with [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

This repo contains a web app for classifying [dim sum](https://en.wikipedia.org/wiki/Dim_sum). It supports 5 dim sum types currently.

----------
## Docker Installation

You can test your changes locally by installing Docker and using the following command:

```
docker build -t dimsum-fastai-v3 . && docker run --rm -it -p 5000:5000 dimsum-fastai-v3
```

----------
## Local Installation

* Install dependencies
```
$ pip install -r requirements.txt
```

## Run app
```
$ python app/server.py serve
```

----------
## Reference

* [Guide for production deployment to Render](https://course.fast.ai/deployment_render.html)

* [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953)
