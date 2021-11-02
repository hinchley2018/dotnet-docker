# Docker dotnet
- put dotnet webapi in docker
- based on https://github.com/dotnet/dotnet-docker/blob/main/samples/aspnetapp/aspnetapp.sln

# Build an image
```bash
docker build --pull -t dotnetapi:v1 .
docker run --rm -it -p 8000:80 dotnetapi:v1

```