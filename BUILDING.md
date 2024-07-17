docker build -t felo:latest .

docker tag felo:latest ghcr.io/felitendo/felo:latest

docker push ghcr.io/felitendo/felo:latest

ON SERVER:

use docker-compose.yml file
