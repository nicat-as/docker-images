FROM alpine

RUN apk add --no-cache python2

RUN wget https://yt-dl.org/downloads/latest/youtube-dl -O /usr/local/bin/youtube-dl

RUN chmod a+rx /usr/local/bin/youtube-dl

RUN apk add ffmpeg