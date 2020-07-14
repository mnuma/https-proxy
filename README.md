- Usage

docker image build --no-cache -t https-proxy:0.1 .
docker container run --rm -p 443:443 --name https-proxy https-proxy:0.1

- Enable

chrome://flags/#allow-insecure-localhost



curl -k https://localhost