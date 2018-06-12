FROM nginx:1.15

RUN apt-get update && \
    apt-get install -y --no-install-recommends ca-certificates git && \
    rm -rf rm -rf /var/lib/apt/lists/*

RUN cd /tmp && \
    git clone https://github.com/cnrancher/cube.git && \
    mv cube/consoles /usr/share/nginx/ && \
    rm -rf cube

COPY default.conf /etc/nginx/conf.d/default.conf
