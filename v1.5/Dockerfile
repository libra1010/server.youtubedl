FROM libra1010/server.base:1.5

RUN exec gosu $USER "curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl"
RUN exec gosu $USER "chmod a+rx /usr/local/bin/youtube-dl"