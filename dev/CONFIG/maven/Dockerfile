FROM atlassianlabs/docker-node-jdk-chrome-firefox

RUN groupadd --gid 1000 sakaibuilder \
  && useradd --uid 1000 --gid sakaibuilder --shell /bin/bash --create-home sakaibuilder

RUN apt update && \
  apt install -y zsh

USER sakaibuilder