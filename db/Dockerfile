FROM postgres:16.2-bookworm

RUN \
    --mount=type=cache,target=/var/cache/apt \
    apt-get update && apt-get install -y postgresql-16-pgvector
