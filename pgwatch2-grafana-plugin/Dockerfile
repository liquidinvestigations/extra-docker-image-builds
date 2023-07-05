FROM cybertec/pgwatch2-postgres:latest

RUN mkdir /grafana-extra-plugins
ADD https://storage.googleapis.com/plugins-community/savantly-heatmap-panel/release/0.2.1/savantly-heatmap-panel-0.2.1.zip /grafana-extra-plugins/

RUN apt-get update && apt-get install -y --no-install-recommends \
unzip \
&&  apt-get clean &&  rm -rf /var/lib/apt/lists/*
