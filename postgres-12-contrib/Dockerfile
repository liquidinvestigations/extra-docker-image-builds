FROM postgresql:11

RUN apt-get update && apt-get install -y --no-install-recommends \
postgresql-contrib \
python3-pip \
python3-dev \
python3-venv \
git \
&& \
apt-get clean && \
rm -rf /var/lib/apt/lists/*
