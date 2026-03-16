FROM ruby:3.3.4

RUN apt-get update && apt-get install -y \
    build-essential \
    git \
    && rm -rf /var/lib/apt/lists/*

RUN gem install bundler github-pages:232

WORKDIR /workspaces
