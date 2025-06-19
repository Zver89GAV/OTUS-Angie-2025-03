sudo apt-get update
sudo apt-get install ca-certificates
sudo apt-get install curl
sudo curl -o /etc/apt/trusted.gpg.d/angie-signing.gpg https://angie.software/keys/angie-signing.gpg
echo "deb https://download.angie.software/angie/$(. /etc/os-release && echo "$ID/$VERSION_ID $VERSION_CODENAME") main" | sudo tee /etc/apt/sources.list.d/angie.list > /dev/null
cat /etc/apt/sources.list.d/angie.list 
sudo apt-get update
sudo apt install angie angie-console-light angie-module-brotli
ps afx
systemctl status angie
sudo nft list ruleset
sudo iptables-save 
ip a
angie -V
sudo apt-get purge angie
sudo rm -r /var/cache/angie/
cd /var/
ls
cd cache/
ls
angie -t
cd /etc/ssl/angie/
sudo chown -R _apt:nogroup /etc/ssl/angie/
sudo apt-get update 
sudo apt-get install apt-transport-https 
sudo apt-get install lsb-release 
sudo apt-get install ca-certificates
sudo apt-get install curl 
sudo apt-get install gnupg2
sudo apt autoremove 
sudo curl -o /etc/apt/trusted.gpg.d/angie-signing.gpg https://angie.software/keys/angie-signing.gpg
echo "deb https://download.angie.software/angie-pro/$(. /etc/os-release && echo "$ID/$VERSION_ID $VERSION_CODENAME") main" | sudo tee /etc/apt/sources.list.d/angie.list > /dev/null
cat /etc/apt/sources.list.d/angie.list 
sudo nano /etc/apt/apt.conf.d/90download-angie
sudo apt-get update
sudo apt-get install angie-pro angie-pro-module-brotli 
ps afx
ip a
sudo angie -t
sudo apt install docker.io 
sudo mkdir /var/www/html
sudo mkdir /var/www
sudo mkdir /var/www/html
sudo nano /var/www/html/index.html
docker run --name -v /var/www/html/:/usr/share/angie/html:ro -p 8800:80 -d docker.angie.software/angie:latest
docker run --name angie -v /var/www/html/:/usr/share/angie/html:ro -p 8800:80 -d docker.angie.software/angie:latest
sudo docker run --name angie -v /var/www/html/:/usr/share/angie/html:ro -p 8800:80 -d docker.angie.software/angie:latest
docker cp angie:/etc/angie/ /home/db/angie
sudo mkdir /home/db/
sudo mkdir /home/db/angie
docker cp angie:/etc/angie/ /home/db/angie
sudo docker cp angie:/etc/angie/ /home/db/angie
sudo docker ps
curl localhost:8800
ps afx
sudo iptables -nvL
ip a
cd /home/db/
ll
sudo docker rm -f angie
sudo docker ps
sudo docker run --name angie_host -v /var/www/html:/usr/share/angie/html:ro -v /home/db/angie/angie:/etc/angie:ro -p 8800:80 -d docker.angie.software/angie:latest
sudo docker ps
sudo docker logs angie_host
sudo docker kill -s HUP angie_host
ps afx
cd ..
ll
sudo angie -T
