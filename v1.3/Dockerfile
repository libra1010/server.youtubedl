FROM libra1010/server.base:1.4

RUN exec gosu $user curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
RUN exec gosu $user chmod a+rx /usr/local/bin/youtube-dl