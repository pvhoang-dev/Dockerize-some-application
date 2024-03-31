#### Now let’s build the Docker image of our Vue.js app:

```bash
docker build -t your-app .
```

#### Finally, let’s run our Vue.js app in a Docker container:

```bash
docker run -it -p 8080:8080 --rm --name vuejs-app your-app

```

#### We should be able to access our Vue.js app on localhost:8080.
