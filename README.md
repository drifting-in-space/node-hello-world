# node-hello-world

```sh
npm install
npm start
```

### Build the container image to run on linux/amd64 platform

```sh
docker build --platform linux/amd64 --tag node-hello-world .
```

Run `docker images` to see the `node-hello-world` image in your list of local images.
