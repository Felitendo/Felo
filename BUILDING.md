docker build -t felo:latest .

docker tag felo:latest ghcr.io/felitendo/felo:latest

docker push ghcr.io/felitendo/felo:latest

ON SERVER:

docker run -d ghcr.io/felitendo/felo:latest -p 3098:3000
