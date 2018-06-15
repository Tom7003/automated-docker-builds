# automated-docker-builds
Automated Docker Builds

##build
$ docker build -t turtlecoin:latest .

## push

## RUN
docker run -v $(pwd)/walletd:/var/lib/walletd -v $(pwd)/turtlecoind:/var/lib/turtlecoind -v $(pwd)/simplewallet:/home/turtlecoin -p 11898:11898 -p 11897:11897 -p 8070:8070 --rm -ti turtlecoind:latest
