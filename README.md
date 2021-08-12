# auth-blog-service

![Actions Workflow](/workflows/go/badge.svg)

## How to Start Development

1. Copy ```sample.env``` to ```.env``` and rename the variables if you need
2. Build the images and run the containers:

```sh
$ cp sample.env .env
$ docker-compose up --build -d
$ docker-compose logs -f api
```

- API: [http://localhost:5000](http://localhost:5000)
