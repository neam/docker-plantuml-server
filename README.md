# docker-plantuml-server

[plantuml-server](https://github.com/plantuml/plantuml-server) in Docker.

## Usage

```sh
# either run in foreground (ctrl-c exits the server)
docker run -it -p 8080:8080 --rm neam/plantuml-server

# or in background (server keeps running until specifically killed)
docker logs -f $(docker run -d -p 8080:8080 neam/plantuml-server)
```

Visit http://ip-of-your-docker-host:8080 in your browser
