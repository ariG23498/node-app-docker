# NODE APP with DOCKER
* Clone the repo
* `cd` into the folder
```bash
$ docker build -t <your name>/<image name>:<version> .
$ docker container run -p <host port>:9090 <your name>/<image name>:<version>
``` 
* In your favourite webbrowser ping to `localhost:<host port>`
