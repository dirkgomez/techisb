build:
	docker pull linuxserver/letsencrypt
run:
	docker run -e techisb.de -p 80:80 -p 443:443 -e EMAIL=operations@techisb.de -e TZ=Europe/Berlin -e URL=techisb.de -e PUID=$(id -u) -e PGID=$(id -g) -v $(PWD)/../config:/config -d linuxserver/letsencrypt
