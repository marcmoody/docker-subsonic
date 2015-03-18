# Subsonic standalone install

Command runs as ENTRYPOINT, so all options should be available.

i.e. to run with https port:
docker run -d -p 44443:4443 -v "/path/to/music:/var/music:ro" marcmoody/subsonic --https-port=4443
