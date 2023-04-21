FROM clojure:latest

RUN cat /etc/os-release

RUN apt-get update
RUN apt-get install -y git-core curl gnupg sudo
RUN curl -fsSL https://deb.nodesource.com/setup_20.x | bash - \
    && sudo apt-get install -y nodejs
