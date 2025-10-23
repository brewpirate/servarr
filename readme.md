# servarr

## Overview

The goal of this project is to avoid having one large `docker-compose.yaml` file and create a core set of services that are imported into a single `docker-compose.yaml`. Modifications are made in `compose.override.yaml` allowing you to track what modificatins you made outside of a working configuration.

## Services

## Start

`docker compose --env-file [your .env] up -d`
