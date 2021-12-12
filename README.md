Based off https://docs.docker.com/samples/dotnetcore/

# Build & Run
1. docker build -t test-web-app .
1. docker run -d -p 8080:80 --name testapp test-web-app