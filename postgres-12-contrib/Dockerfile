FROM postgres:12

RUN apt-get update && apt-get install -y --no-install-recommends \
postgresql-contrib \
&&  apt-get clean &&  rm -rf /var/lib/apt/lists/*
