# Docker Collection
This repo pretends to be the most complete collection of docker containers for every use case.
## Motivation
A lot of guides and list of best docker containers are already out in the web. Docker itself is a mature technology and widely spread. In 2022 where web is increasing its capabilities and more people can and want to build their own server for whatever reasons, this repo wants to help in exploring all the capabilities the open source comunity can provide to them.
## Structure
The repo provide first different use case scenario, with docker-compose files and integration suites. Every people has their needs, not everyone want to store their film library but rather need to have their GitLab server.

Next a complete list is presented, grouped by sector.

# Table of contents

<!--ts-->
   * [First things first](#first-things-first)
   * [Use scenario](#use-scenario)
   * [Categories](#categories)
<!--te-->

First things first
============
Every deployment needs some software to easily manage containers or the full system.  
The first container you need to install is:  
 * **Portainer**\
 This is a must-have software for easy management of containers, stacks and whatever related to docker. Allow to easily monitor logs for every container, configuration and include the console connection.\
 [Docker Hub link](https://hub.docker.com/r/portainer/portainer)
 * **Heimdall**\
 Ok, not exactly necessary, but if you start deploying a lot of containers on different local ports, a place to store every link could be useful.\
 [Docker Hub link](https://hub.docker.com/r/linuxserver/heimdall)

Use scenario
============
### Not so simple user
This scenario is for new docker users that simply want to enjoy the docker world but do not have all the knowledge to configure technical parameters.
 * **Nextcloud**\
 A complete platform to store files, share with others, manage photo library, sync files with pc or phones (like OneDrive), complete with useful plugines like gpx file manager, phone tracker, mind map creator, office suite etc.\
 It's a good replacement for Google services, with the advantage of being open source and all data are stored locally. It offers a calendar which can be synchronized with pc and phone, an activity manager for work scheduling and a mail utility to read emails in one place via browser.\
 [Docker Hub link](https://hub.docker.com/_/nextcloud)
 * **DokuWiki**\
 Light wiki, useful for rapid notes with permission manager. Write in markdown and add also images stored inside the container itself.\
 [Docker Hub link](https://hub.docker.com/r/bitnami/dokuwiki)
 * **MariaDB**\
 Along with Nextcloud, a DB is required. MariaDB is one solution.\
 [Docker Hub link](https://hub.docker.com/_/mariadb)
 * **PHP My Admin**\
 To easily manage databases, users and to check if all works fine, PHP My Admin offers a graphical utility to manage the MariaDB engine.\
 [Docker Hub link](https://hub.docker.com/_/phpmyadmin)
 * **Cockpit**\
 If you are not a geek or if you simply prefer to have a nice interface, Cockpit gives you the opportunity to control your system via web.\
 [Docker Hub link](https://hub.docker.com/r/cockpit/ws)
 * **Cludflare DDNS**\
 This is a not-so much technical solution to resolve the dynamic IP limitation if you aim to buy your own domain. It allows to periodically check if cloudflare DNS points to your actual IP.\
 [Docker Hub link](https://hub.docker.com/r/oznu/cloudflare-ddns)
 * **Wordpress**\
 If you plan to buy a domain, maybe you want to build up a website to show your bricolage or a forum to discuss of car racing. Whatever the goal is, Wordpress could be a free solution to get you covered.\
 [Docker Hub link](https://hub.docker.com/_/wordpress)
### Software developer
 * **GitLab**\
 If you are a software designer I don't need to explain what this software does. You only need to know you can host for free the service limited only by your architecture and disk space. Of course you can share with external world your repos.\
 [Docker Hub link](https://hub.docker.com/r/gitlab/gitlab-ce)

Categories
============
### For software develop
 * **GitLab**\
 [Docker Hub link](https://hub.docker.com/r/gitlab/gitlab-ce)
 * **Gitea**\
 A painless, self-hosted Git service.\
 [Docker Hub link](https://hub.docker.com/r/gitea/gitea)
 * **Icecoder**\
 ICEcoder is a browser based code editor, which provides a modern approach to building websites.\
 [Official site](https://icecoder.net/)
 * **Jupyter**\
 JupyterLab is the latest web-based interactive development environment for notebooks, code, and data. Its flexible interface allows users to configure and arrange workflows in data science, scientific computing, computational journalism, and machine learning.\
 Depending on your needs, you can find a lot of different containers already implementing useful python packages such as scipy.
 [Official site](https://jupyter.org/) - [Docker Hub link](https://hub.docker.com/r/johntrimble/jupyter-multiarch)
 * **VScode**\
 Run VS Code on any machine anywhere and access it through the browser.\
 [On GitHub](https://github.com/coder/code-server) [Docker Hub link](https://hub.docker.com/r/codercom/code-server)
### Networking
 * **Wireguard**\
 WireGuard is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache.\
 [On GitHub](https://github.com/linuxserver/docker-wireguard) - [Official site](https://www.wireguard.com/) - [Docker Hub link](https://hub.docker.com/r/linuxserver/wireguard)
 * **Pi-Hole + Unbound**\
 Network-wide Ad Blocking with DHCP functionalities.\
 [Pi-hole official site](https://pi-hole.net/) - [On GitHub](https://github.com/chriscrowe/docker-pihole-unbound) - [Docker Hub link]()
 * **Traefik**\
 Traefik is an open-source Edge Router that makes publishing your services a fun and easy experience. It receives requests on behalf of your system and finds out which components are responsible for handling them.\
 [Official site](https://traefik.io/) [Docker Hub link](https://hub.docker.com/_/traefik)
 * ****\
 \
 [On GitHub]() - [Official site]() [Docker Hub link]()
 

### For administrators
 * **Rancher**\
 Rancher provides detailed management of all aspects of infrastructure and of course Docker as well such as host, containers, storage pools, and the container registry.\
 [Official site](https://rancher.com/) - [Docker Hub link](https://hub.docker.com/r/rancher/rancher)
 * **Kitematic**\
 Kitematic is an official graphical user interface (GUI) tool to manage Docker, provided by docker-group itself.\
 [Docker Hub link](https://hub.docker.com/r/kitematic/hello-world-nginx)
 * **Portainer**\
 A light administrator tool to easily manage containers, networks, volumes and all resources connected to docker.\
 [Official site](https://www.portainer.io/) - [Docker Hub link](https://hub.docker.com/r/portainer/portainer)
 * **Cockpit**\
 Cockpit is a web-based graphical interface for servers, intended for everyone.\
 [Official site](https://cockpit-project.org/) - [Docker Hub link](https://hub.docker.com/r/cockpit/ws)
 * **Guacamole**\
 Apache Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH. No need for any plugin, easily accessible via browser.\
 [Official site](https://guacamole.apache.org/) - [Docker Hub link](https://hub.docker.com/r/oznu/guacamole)
 * **Scrutiny**\
 WebUI for smartd S.M.A.R.T monitoring.\
 [On GitHub](https://github.com/AnalogJ/scrutiny) - [Docker Hub link](https://hub.docker.com/r/linuxserver/scrutiny)
 * **Authelia**\
 Authelia (Lite) - Self-Hosted Single Sign-On and Two-Factor Authentication\
 [Official site](https://www.authelia.com/) - [Docker Hub link](https://hub.docker.com/r/authelia/authelia)
 * **Statping**\
 Statping - Web and App Status Monitoring for Any Type of Project.\
 [On GitHub](https://github.com/statping/statping) - [Docker Hub link](https://hub.docker.com/r/statping/statping)
 * ****\
 \
 [On GitHub]() - [Official site]() [Docker Hub link]()

### Multimedia
 * **Handbrake**\
 HandBrake is a tool for converting video from nearly any format to a selection of modern, widely supported codecs. The container expose the GUI via web and allow the auto-conversion whenever a file is copied into a folder.\
 [On GitHub](https://github.com/jlesage/docker-handbrake) - [Docker Hub link](https://hub.docker.com/r/jlesage/handbrake)
 * **Lidarr**\
 Lidarr is a music collection manager for Usenet and BitTorrent users.\
 [Official site](https://lidarr.audio/) - [Docker Hub link](https://hub.docker.com/r/linuxserver/lidarr)
 * **Sonarr**\
 Sonarr is a PVR for Usenet and BitTorrent users.\
 [Official site](https://sonarr.tv/) - [Docker Hub link](https://hub.docker.com/r/linuxserver/sonarr)
 * ****\

 [Official site]() - [Docker Hub link]()
 * **Photoshow**\
 Photoshow is gallery software at its easiest, it doesn't even require a database.\
 [On GitHub](https://github.com/linuxserver/docker-photoshow) - [Docker Hub link](https://hub.docker.com/r/linuxserver/photoshow)

### Productivity
 * **Joplin**\
 Joplin is an open source note-taking app. Can be accessed by many devices. Notes are written in markdown style. You can run yuor own server docker for free.
 [Official site](https://joplinapp.org/) - [Docker Hub link](https://hub.docker.com/r/joplin/server)
 * **DokuWiki**\
 Light wiki, useful for rapid notes with permission manager. Write in markdown and add also images stored inside the container itself.\
 [Official site](https://www.dokuwiki.org/) - [Docker Hub link](https://hub.docker.com/r/bitnami/dokuwiki)


 [Official site]() - [Docker Hub link]()
### Others
 * **ArchiveBox**\
 ArchiveBox is a powerful, self-hosted internet archiving solution to collect, save, and view sites you want to preserve offline.\
 [Official site](https://archivebox.io/) - [Docker Hub link](https://hub.docker.com/r/archivebox/archivebox)
 * **Organizr**\
 Organizr aims to be your one stop shop for your Servers Frontend.\
 [Official site](https://organizr.app/) - [Docker Hub link](https://hub.docker.com/r/organizr/organizr)
 * ****\

 [Official site]() - [Docker Hub link]()

