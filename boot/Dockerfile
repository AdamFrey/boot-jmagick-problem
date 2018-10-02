FROM clojure:boot

RUN apt-get update
RUN apt-get install -y imagemagick libjmagick6-java

WORKDIR /App

COPY build.boot .
COPY magick_script.clj .
