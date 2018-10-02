FROM clojure:lein

RUN apt-get update
RUN apt-get install -y imagemagick libjmagick6-java

WORKDIR /App

COPY project.clj .
COPY magick_script.clj .
