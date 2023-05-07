# mcrdt_sysadmin_devops

Mon Centre de Recherche et développement technologique (MCRDT)

> Toutes les configurations que je réalise dans le domaine de l'administration système
> ça pourra m'aider moi même et de plus faciliter la tâche au newbie de Linux de s'en sortir très facilement

- Linux,
- DNS,
- Serveur Web,
- Certificat SSL (auto signé),
- Cerbot (Let's Encrypt)
- DevOPS

  - Docker
  - Ansible
  - AWS
  - Grafana
  - Openstack

- Solution implémentée ...

## Docker deployement guide
```bash
$ cd mcrdt_sysadmin_devops
$ docker-compose up -d # to start the docker and download images
# check localhost:8090 for the web server, you will see a login page
# check localhost:8091 for the phpmyadmin, login with
                        # user root
                        # pwd  find the it in the file and change it
```

## Navigation tree
```bash
README.md
backup_sql_db.sh   
dns.html
dns.md
docker-compose.yaml
email_template.html
geo.Dockerfile     
html
   |-- index.php
network_script_utils.sh
vimrc.conf
```
