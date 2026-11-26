FROM postgis/postgis:16-3.6

RUN apt-get update \
    && apt-get -y install --no-install-recommends \
    postgresql-16 \
    postgresql-16-postgis-3 \
    unzip \
    curl \
    wget \
    osm2pgsql

WORKDIR /work