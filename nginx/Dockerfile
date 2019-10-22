# docker build . -t gcr.io/prysmaticlabs/prysm/testnet-proxy-cache:latest
FROM nginx:1.17.5-alpine

COPY default.conf /etc/nginx/conf.d/

CMD ["nginx", "-g", "daemon off;"]

