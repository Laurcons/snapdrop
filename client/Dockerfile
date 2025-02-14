FROM nginx:alpine

WORKDIR /usr/share/nginx/html
COPY images images
COPY scripts scripts
COPY sounds sounds
COPY index.html .
COPY manifest.json .
COPY service-worker.js .
COPY styles.css .

COPY nginx/default.conf /etc/nginx/conf.d/default.conf