[Optional install-docker if Docker not install]

0. $ bash -c "$(wget -qLO - https://raw.githubusercontent.com/bigbeartechworld/big-bear-scripts/master/install-docker/run.sh)"

# install-traccar

1. $ bash -c "$(wget -qLO - https://raw.githubusercontent.com/zafims/install-traccar/main/run.sh)"

2. $ mkdir docker-script/traccar -p
3. $ cd docker-script/traccar
4. $ wget https://raw.githubusercontent.com/zafims/install-traccar/main/docker-compose.yml
5. $ docker-compose up


---> Web Access: [IP Address]:8082 <---

admin/admin

======================== Install TracCar Manually =========================

$ wget https://github.com/traccar/traccar/releases/download/v6.0/traccar-linux-64-6.0.zip

$ ls

$ unzip traccar-linux-64-6.0.zip

$ sudo ./traccar.run

$ sudo systemctl start traccar

====================== install-traccar-kubernetes ==========================

https://github.com/zafims/install-traccar-kubernetes
