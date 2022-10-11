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

If this list is not exaustive, you can find others in [Crazymax](https://hub.docker.com/u/crazymax)

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
 Depending on your needs, you can find a lot of different containers already implementing useful python packages such as scipy.\
 [Official site](https://jupyter.org/) - [Docker Hub link](https://hub.docker.com/r/johntrimble/jupyter-multiarch)
 * **VScode**\
 Run VS Code on any machine anywhere and access it through the browser.\
 [On GitHub](https://github.com/coder/code-server) - [Docker Hub link](https://hub.docker.com/r/codercom/code-server)
 * **Haste**\
 Haste is an open-source pastebin software written in node.js, which is easily installable in any network. It can be backed by either redis or filesystem, and has a very easy adapter interface for other stores.\
 [On GitHub](https://github.com/toptal/haste-server) - [Docker Hub link](https://hub.docker.com/r/jonasled/haste-server)
 * **Privatebin**\
 PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.\
 [Official site](https://privatebin.info/) - [Docker Hub link](https://hub.docker.com/r/privatebin/nginx-fpm-alpine)
 * **Matomo**\
 Google Analytics alternative that protects your data and your customers' privacy.\
 [Official site](https://matomo.org/) - [Docker Hub link](https://hub.docker.com/_/matomo)
 * **Thingsboard**\
 Open-source IoT Platform - Device management, data collection, processing and visualization.\
 [Official site](https://thingsboard.io/)
 * **Webtop**\
 Webtop - Alpine, Ubuntu, Fedora, and Arch based containers containing full desktop environments in officially supported flavors accessible via any modern web browser.\
 [LinuxServer site](https://docs.linuxserver.io/images/docker-webtop) - [On GitHub](https://github.com/linuxserver/docker-webtop)
 * **Typebot**\
 Typebot is an open-source alternative to Landbot. It allows you to create conversational apps/forms (Lead qualification, Product launch, User onboarding, Customer support), embed them anywhere on your web/mobile apps, and collect results in real-time.\
 [Official Site](https://docs.typebot.io/self-hosting/docker)

### Networking
 * **Wireguard**\
 WireGuard is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache.\
 [On GitHub](https://github.com/linuxserver/docker-wireguard) - [Official site](https://www.wireguard.com/) - [Docker Hub link](https://hub.docker.com/r/linuxserver/wireguard)
 * **Pi-Hole + Unbound**\
 Network-wide Ad Blocking with DHCP functionalities.\
 [Pi-hole official site](https://pi-hole.net/) - [On GitHub](https://github.com/chriscrowe/docker-pihole-unbound) - [Docker Hub link]()
 * **Traefik**\
 Traefik is an open-source Edge Router that makes publishing your services a fun and easy experience. It receives requests on behalf of your system and finds out which components are responsible for handling them.\
 [Official site](https://traefik.io/) - [Docker Hub link](https://hub.docker.com/_/traefik)* **Traefik**\
 * **OpenVPN**
 DockOvpn is an out of the box dockerized OpenVPN server, which starts in just a few seconds and runs forever.\
 [On GitHub](https://github.com/dockovpn/docker-openvpn) - [Official site](https://dockovpn.io/) - [Docker Hub link](https://hub.docker.com/r/kylemanna/openvpn)
 * **OpenVPN monitor**
 OpenVPN Monitor is a web-based utility that displays the status of OpenVPN servers. It includes information such as the usernames/hostnames connected, remote and VPN IP addresses, approximate locations (using GeoIP), traffic consumption and more.\
 [On GitHub](https://github.com/ruimarinho/docker-openvpn-monitor) - [Docker Hub link](https://hub.docker.com/r/ruimarinho/openvpn-monitor)
 * **OpenVPN Web UI**\
 OpenVPN server web administration interface.Goal: create quick to deploy and easy to use solution that makes work with small OpenVPN environments a breeze.\
 [On GitHub](https://github.com/adamwalach/openvpn-web-ui#Prod=)
 * **Wireguard**\
 WireGuard is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache.\
 [On GitHub](https://github.com/linuxserver/docker-wireguard) - [Docker Hub link](https://hub.docker.com/r/linuxserver/wireguard)
 * **Pi.Alert**\
 Scan the devices connected to your WIFI / LAN and alert you the connection of unknown devices. It also warns the disconnection of "always connected" devices.\
 [On GitHub](https://github.com/pucherot/Pi.Alert) - [Docker Hub link](https://registry.hub.docker.com/r/jokobsk/pi.alert)
 * **ProtonVPN**\
 [On GitHub](https://github.com/tprasadtp/protonvpn-docker)
 * **Gravity Sync**\
 Sync two pi-hole instances.\
 [On GitHub](https://github.com/vmstan/gravity-sync)
 * **Tinyproxy**\
 A quick and easy Dockerised Tinyproxy with configurable ACL.\
 [On GitHub](https://github.com/monokal/docker-tinyproxy)
 
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
 Authelia (Lite) - Self-Hosted Single Sign-On and Two-Factor Authentication.\
 [Official site](https://www.authelia.com/) - [Docker Hub link](https://hub.docker.com/r/authelia/authelia)
 * **Statping**\
 Statping - Web and App Status Monitoring for Any Type of Project.\
 [On GitHub](https://github.com/statping/statping) - [Docker Hub link](https://hub.docker.com/r/statping/statping)
 * **Ciao**\
 ciao checks HTTP(S) URL endpoints for a HTTP status code (or errors on the lower TCP stack) and sends a notification on status change via E-Mail or Webhooks.\
 [On GitHub](https://github.com/brotandgames/ciao)
 * **Open Speed Test**\
 Openspeedtest - HTML5 Internet Speed Test. no Flash or Java! Broadband Speed Test That Works on Any Web Browser.\
 [Official Site](https://openspeedtest.com/) - [Docker Hub link](https://hub.docker.com/r/openspeedtest/latest)
 * **Glances**\
 Glances is a cross-platform monitoring tool which aims to present a large amount of monitoring information through a curses or Web based interface. The information dynamically adapts depending on the size of the user interface.\
 [On GitHub](https://github.com/nicolargo/glances) - [Docker Hub link](https://hub.docker.com/r/nicolargo/glances)
 * **Baseimage-gui**\
 This is a docker baseimage that can be used to create containers able to run any X application on a headless server very easily. The application's GUI is accessed through a modern web browser or via any VNC client.\
 [On GitHub](https://github.com/jlesage/docker-baseimage-gui) - [Docker Hub link](https://hub.docker.com/r/jlesage/baseimage-gui)
 * **Webmap**\
 Webmap is a very nice frontend browser based user interface for viewing the output of nmap commands generating xml.\
 [On GitHub](https://github.com/SabyasachiRana/WebMap)
 * **Maintenance page**\
 Light and ready to deploy static maintenance page.\
 [On GitHub](https://github.com/wickerlabs/maintenance)
 * **Webproxy**\
 Web proxy for Docker containers. Inspired jwilder/nginx-proxy.\
 [On GitHub](https://github.com/odoku/docker-webproxy)
 * **Observium**\
 Observium is a low-maintenance auto-discovering network monitoring platform supporting a wide range of device types, platforms and operating systems including Cisco, Windows, Linux, HP, Juniper, Dell, FreeBSD, Brocade, Netscaler, NetApp and many more.\
 [Official documentation](https://docs.observium.org/) - [Official site](https://observium.org)

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
 * **MakeMKV**\
 MakeMKV is a format converter, otherwise called "transcoder". It converts the video clips from proprietary (and usually encrypted) disc into a set of MKV files, preserving most information but not changing it in any way.\
 [On GitHub](https://github.com/jlesage/docker-makemkv) - [Docker Hub link](https://hub.docker.com/r/jlesage/makemkv/)
 * **Photoshow**\
 Photoshow is gallery software at its easiest, it doesn't even require a database.\
 [On GitHub](https://github.com/linuxserver/docker-photoshow) - [Docker Hub link](https://hub.docker.com/r/linuxserver/photoshow)
 * **Audiobook Shelf**\
 AudioBookshelf is a self-hosted audiobook server for managing and playing your audiobooks.\
 [On GitHub](https://github.com/advplyr/audiobookshelf-app)

### Productivity
 * **Joplin**\
 Joplin is an open source note-taking app. Can be accessed by many devices. Notes are written in markdown style. You can run your own server docker for free.
 [Official site](https://joplinapp.org/) - [Docker Hub link](https://hub.docker.com/r/joplin/server)
 * **DokuWiki**\
 Light wiki, useful for rapid notes with permission manager. Write in markdown and add also images stored inside the container itself.\
 [Official site](https://www.dokuwiki.org/) - [Docker Hub link](https://hub.docker.com/r/bitnami/dokuwiki)
 * **Vaultwarden**\
 Alternative implementation of the Bitwarden server API written in Rust and compatible with upstream Bitwarden clients, perfect for self-hosted deployment where running the official resource-heavy service might not be ideal. A password manager solution with web, PC and phone support.\
 [On GitHub](https://github.com/dani-garcia/vaultwarden) - [Docker Hub link](https://hub.docker.com/r/vaultwarden/server)
 * **Overleaf**\
 An open-source online real-time collaborative LaTeX editor.\
 [On GitHub](https://github.com/overleaf/overleaf) - [Docker Hub link](https://hub.docker.com/r/sharelatex/sharelatex)
 * **Paperless-ng**\
 Paperless is an application that indexes your scanned documents and allows you to easily search for documents and store metadata alongside your documents. The Android app allows to connect to your server. \
 [On GitHub](https://github.com/jonaswinkler/paperless-ng) - [Docker Hub link](https://hub.docker.com/r/jonaswinkler/paperless-ng)
 * **Gotenberg**\
 Gotenberg provides a developer-friendly API to interact with powerful tools like Chromium and LibreOffice for converting numerous document formats (HTML, Markdown, Word, Excel, etc.) into PDF files, and more! \
 You should also install [this web client](https://github.com/gotenberg/gotenberg-php). \
 [Official site](https://gotenberg.dev/) - [On GitHub](https://github.com/gotenberg/gotenberg) - [Docker Hub link](https://hub.docker.com/r/gotenberg/gotenberg)
 * **Asterisk**\
 Asterisk is an open source framework for building communications applications. Asterisk turns an ordinary computer into a communications server. \
 [Official site](https://www.asterisk.org/) - [Docker Hub link](https://hub.docker.com/r/dougbtv/asterisk/#!)
 * **0bin**\
 Asterisk is an open source framework for building communications applications. Asterisk turns an ordinary computer into a communications server. \
 [Official site](https://www.asterisk.org/) - [Docker Hub link](https://hub.docker.com/r/dougbtv/asterisk/#!)
 * **Webpdf**\
 Asterisk is an open source framework for building communications applications. Asterisk turns an ordinary computer into a communications server. \
 [Official site](https://www.webpdf.de/) - [Docker Hub link](https://hub.docker.com/r/softvisiondev/webpdf)
 * **Outline**\
 A fast, collaborative, knowledge base for your team built using React and Node.js.\
 [Official site](https://www.getoutline.com/) - [Docker Hub link](https://hub.docker.com/r/outlinewiki/outline)
 * **Web PDF Toolbox**\
 Very simple web toolbox to combine, compress, split PDF, and convert between images and PDF, change contrast of PDF, and add text watermark on PDF using Ghostscript and ImageMagick. \
 This container aims to make available many useful pdf tools. This is the only application found but unfortunately for me doesn't work.\
 [On GitHub](https://github.com/natpuch/web-pdf-toolbox)
 * **emails-html-to-pdf**\
 This script will check an imap folder for unread emails. Any unread email that does not have an attachment will be converted to a pdf and then emailed to the address you specify. The script is run at a configurable interval.\
 [On GitHub](https://github.com/rob-luke/emails-html-to-pdf)

### Others
 * **ArchiveBox**\
 ArchiveBox is a powerful, self-hosted internet archiving solution to collect, save, and view sites you want to preserve offline.\
 [Official site](https://archivebox.io/) - [Docker Hub link](https://hub.docker.com/r/archivebox/archivebox)
 * **Organizr**\
 Organizr aims to be your one stop shop for your Servers Frontend.\
 [Official site](https://organizr.app/) - [Docker Hub link](https://hub.docker.com/r/organizr/organizr)
 * **Remotely**\
 A remote control and remote scripting solution, built with .NET 5, Blazor, SignalR Core, and WebRTC.\
 [On GitHub](https://github.com/immense/Remotely) - [Docker Hub link](https://hub.docker.com/r/translucency/remotely)
 * **Home Bridge**\
 [Official Site](https://homebridge.io/)
 * **Firefox Sync server**\
 [Official documentation](https://moz-services-docs.readthedocs.io/en/latest/howtos/run-sync-1.5.html)