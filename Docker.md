# Docker

--- | --- |
Start | `open -a Docker`
Prune | `docker system prune`
Build Image | `docker build -t <new image> -f <base file> .`
Remove Images | `docker rmi $(docker images -qf "dangling=true")`
Stop Containers | `docker stop $(docker ps -a -q)`
Remove Containers | `docker rm $(docker ps -a -q)`
Run Bash | `docker run -it <image> bash`
Get IP | `docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' <container>`
