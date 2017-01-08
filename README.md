# A simple Docker server with Express, Node, Kitematic.

### Demo
![2017-01-08 17 26 32](https://cloud.githubusercontent.com/assets/19645990/21754134/fc08429c-d5c7-11e6-87b7-4b38e04fcb91.gif)

### Tools
* Nodejs
* Expressjs
  * body parsing middleware
* Docker
* Kitematic

### command used

```
docker build .
docker run -t {tag name}
docker ps
```

`curl -H "Content-Type: application/json" -X POST -d '{"hello": "hello world"}' http://localhost:1110/event`

### References
https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
https://www.youtube.com/watch?v=NRrgtUJnkIo&index=9&list=PL0zVEGEvSaeGPBRt-y2QZ3wh64XAe40jx
