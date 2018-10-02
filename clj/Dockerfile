FROM clojure:tools-deps

RUN apt-get update
RUN apt-get install -y imagemagick libjmagick6-java

WORKDIR /App

COPY deps.edn .
COPY magick_script.clj .
