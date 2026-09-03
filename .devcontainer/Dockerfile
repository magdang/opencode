FROM oven/bun:1.3.14

RUN apt-get update \
  && apt-get install --yes --no-install-recommends build-essential git lcov python3 \
  && rm -rf /var/lib/apt/lists/*

USER bun
