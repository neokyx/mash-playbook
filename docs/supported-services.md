<!--
SPDX-FileCopyrightText: 2023 - 2024 Julian-Samuel Gebühr
SPDX-FileCopyrightText: 2023 - 2024 Sergio Durigan Junior
SPDX-FileCopyrightText: 2023 - 2025 MASH project contributors
SPDX-FileCopyrightText: 2023 - 2025 Slavi Pantaleev
SPDX-FileCopyrightText: 2023 Alejandro AR
SPDX-FileCopyrightText: 2023 Nikita Chernyi
SPDX-FileCopyrightText: 2024 Katherine Door
SPDX-FileCopyrightText: 2024 Oliver Lorenz
SPDX-FileCopyrightText: 2025 Gergely Horváth
SPDX-FileCopyrightText: 2025 Suguru Hirahara
SPDX-FileCopyrightText: 2025 XHawk87

SPDX-License-Identifier: AGPL-3.0-or-later
-->

# Supported services

|              Name              |              Description              | Documentation |
| ------------------------------ | ------------------------------------- | ------------- |
| [AUX](https://github.com/mother-of-all-self-hosting/ansible-role-aux) | Auxiliary file/directory management on your server via Ansible | [Link](services/auxiliary.md) |
| [AdGuard Home](https://adguard.com/en/adguard-home/overview.html/) | A network-wide DNS software for blocking ads & tracking | [Link](services/adguard-home.md) |
| [Anki](https://docs.ankiweb.net/sync-server.html) | Self-hosted synchronization server for Anki, a flashcard program that helps you spend more time on challenging material, and less on what you already know | [Link](services/anki.md) |
| [AnonymousOverflow](https://github.com/httpjamesm/AnonymousOverflow) | View StackOverflow threads without exposing your IP address, browsing habits, and other browser fingerprinting data to the website | [Link](services/anonymousoverflow.md) |
| [APISIX Dashboard](https://apisix.apache.org/docs/dashboard/USER_GUIDE/) | A web UI for [APISIX Gateway](services/apisix-gateway.md) | [Link](services/apisix-dashboard.md) |
| [APISIX Gateway](https://apisix.apache.org/docs/apisix/getting-started/README/) | An API Gateway, Ingress Controller, etc | [Link](services/apisix-gateway.md) |
| [Appsmith](https://www.appsmith.com/) | Platform for building and deploying custom internal tools and applications without writing code | [Link](services/appsmith.md) |
| [Authelia](https://www.authelia.com/) | An open-source authentication and authorization server that can work as a companion to [common reverse proxies](https://www.authelia.com/overview/prologue/supported-proxies/) (like [Traefik](services/traefik.md) frequently used by this playbook) | [Link](services/authelia.md) |
| [authentik](https://goauthentik.io/) | An open-source Identity Provider focused on flexibility and versatility. | [Link](services/authentik.md) |
| [Autobrr](https://autobrr.com/) |  Modern, easy to use download automation for torrents and usenet.  | [Link](services/autobrr.md) |
| [BorgBackup](https://www.borgbackup.org/) (via [borgmatic](https://torsion.org/borgmatic/)) | A deduplicating backup program with optional compression and encryption| [Link](services/backup-borg.md) |
| [Calibre-Web](https://github.com/janeczku/calibre-web) | Web app for browsing, reading and downloading eBooks stored in a [Calibre](https://calibre-ebook.com/) database | [Link](services/calibre-web.md) |
| [Changedetection.io](https://github.com/dgtlmoon/changedetection.io) | A simple website change detection and restock monitoring solution. | [Link](services/changedetection.md) |
| [ClickHouse](https://clickhouse.com/) | An open-source column-oriented DBMS for online analytical processing (OLAP) that allows users to generate analytical reports using SQL queries in real-time. | [Link](services/clickhouse.md) |
| [Collabora Online](https://www.collaboraoffice.com/) | Your Private Office Suite In The Cloud | [Link](services/collabora-online.md) |
| [ConvertX](https://github.com/C4illin/ConvertX) | Self-hosted online file converter for pictures, video, images, document files, etc. | [Link](services/convertx.md) |
| [CouchDB](https://couchdb.apache.org/) | An open-source document-oriented NoSQL database, implemented in Erlang. | [Link](services/couchdb.md) |
| [Docker](https://www.docker.com/) | Open-source software for deploying containerized applications | [Link](services/docker.md) |
| [Docker Registry](https://docs.docker.com/registry/) | A container image distribution registry | [Link](services/docker-registry.md) |
| [Docker Registry Browser](https://github.com/klausmeyer/docker-registry-browser) | Web Interface for the Docker Registry HTTP API V2 written in Ruby on Rails | [Link](services/docker-registry-browser.md) |
| [Docker Registry Proxy](https://github.com/etkecc/docker-registry-proxy) | Pass-through docker registry (distribution) proxy with metadata caching, docker-compatible errors, prometheus metrics, etc. | [Link](services/docker-registry-proxy.md) |
| [Docker Registry Purger](https://github.com/devture/docker-registry-purger) | A small tool used for purging a private Docker Registry's old tags | [Link](services/docker-registry-purger.md) |
| [Docmost](https://docmost.com/) | Open-source collaborative wiki and documentation software | [Link](services/docmost.md) |
| [DokuWiki](https://dokuwiki.org/) | A lightweight, file-based wiki engine with intuitive syntax and no database requirements | [Link](services/dokuwiki.md) |
| [Echo IP](https://github.com/mpolden/echoip) | A simple service for looking up your IP address | [Link](services/echoip.md) |
| [Endlessh-go](https://github.com/shizunge/endlessh-go) | A golang implementation of Endlessh, an SSH tarpit | [Link](services/endlessh.md) |
| [etcd](https://etcd.io/) | A distributed, reliable key-value store for the most critical data of a distributed system | [Link](services/etcd.md) |
| [Etherpad](https://etherpad.org) | Open source collaborative text editor | [Link](services/etherpad.md) |
| [Excalidraw](https://excalidraw.com/) | Virtual whiteboard for sketching hand-drawn like diagrams | [Link](services/excalidraw.md) |
| [Excalidraw collaboration server](https://github.com/excalidraw/excalidraw-room) | Self-hosted collaboration server for Excalidraw instance | [Link](services/excalidraw-room.md) |
| [exim-relay](https://github.com/devture/exim-relay) | A lightweight [Exim](https://www.exim.org/) SMTP mail relay server | [Link](services/exim-relay.md) |
| [Firezone](https://www.firezone.dev/) | A self-hosted VPN server (based on [WireGuard](https://www.wireguard.com/)) with a Web UI | [Link](services/firezone.md) |
| [FMD Server](https://gitlab.com/fmd-foss/fmd-server) | Official server for FMD (FindMyDevice) | [Link](services/fmd-server.md) |
| [Focalboard](https://www.focalboard.com/) | An open source, self-hosted alternative to [Trello](https://trello.com/), [Notion](https://www.notion.so/), and [Asana](https://asana.com/). | [Link](services/focalboard.md) |
| [Forgejo](https://forgejo.org/) | A self-hosted lightweight software forge (Git hosting service, etc). An alternative to [Gitea](./services/gitea.md). | [Link](services/forgejo.md) |
| [Forgejo Runner](https://code.forgejo.org/forgejo/runner) | A runner to use with Forgejo Actions | [Link](services/forgejo-runner.md) |
| [Freescout](https://freescout.net/) | A free help desk software | [Link](services/freescout.md) |
| [FreshRSS](https://freshrss.org/) | RSS and Atom feed aggregator. | [Link](services/freshrss.md) |
| [Funkwhale](https://funkwhale.audio/) | Listen and share music with a selfhosted streaming server.| [Link](services/funkwhale.md) |
| [Ghostfolio](https://ghostfol.io/) | Wealth management free software to keep track of assets such as stocks, bonds, ETFs, etc.| [Link](services/ghostfolio.md) |
| [Gitea](https://gitea.io/) | A painless self-hosted [Git](https://git-scm.com/) service. | [Link](services/gitea.md) |
| [GoToSocial](https://gotosocial.org/) | A self-hosted [ActivityPub](https://activitypub.rocks/) social network server | [Link](services/gotosocial.md) |
| [Grafana](https://grafana.com/) | An open and composable observability and data visualization platform, often used with [Prometheus](services/prometheus.md) | [Link](services/grafana.md) |
| [Grafana Loki](https://grafana.com/docs/loki/latest/) | Open-source log aggregation system that helps collect, store, and analyze logs in a scalable and efficient manner | [Link](services/grafana-loki.md) |
| [Headscale](https://headscale.net/) | A Tailscale-compatible control server for managing Tailscale devices | [Link](services/headscale.md) |
| [Healthchecks](https://healthchecks.io/) | A simple and Effective Cron Job Monitoring solution | [Link](services/healthchecks.md) |
| [Homarr](https://homarr.dev/) | Highly customizable dashboard for management of your favorite applications and services with a drag-and-drop grid system | [Link](services/homarr.md) |
| [Hubsite](https://github.com/moan0s/hubsite) | A simple, static site that shows an overview of the available services | [Link](services/hubsite.md) |
| [Ihatemoney](https://github.com/spiral-project/ihatemoney) | An open source shared budget manager. | [Link](services/ihatemoney.md) |
| [ILMO](https://github.com/moan0s/ILMO2) | An open source library management tool. | [Link](services/ilmo.md) |
| [Infisical](https://infisical.com/) | An open-source end-to-end encrypted platform for securely managing secrets and configs across your team, devices, and infrastructure. | [Link](services/infisical.md) |
| [InfluxDB](https://www.influxdata.com/) | A self-hosted time-series database. | [Link](services/influxdb.md) |
| [Jackett](https://github.com/Jackett/Jackett) | An API for your favorite torrent trackers | [Link](services/jackett.md) |
| [Jellyfin](https://github.com/jellyfin/jellyfin) | An open-source personal media server | [Link](services/jellyfin.md) |
| [Jitsi](https://jitsi.org/) | A fully encrypted, 100% Open Source video conferencing solution | [Link](services/jitsi.md) |
| [Joplin Server](https://joplinapp.org/help/dev/spec/architecture#joplin-server) | Self-hosted server component for [Joplin](https://joplinapp.org/) | [Link](services/joplin-server.md) |
| [Keycloak](https://www.keycloak.org/) | An open source identity and access management solution. | [Link](services/keycloak.md) |
| [KeyDB](https://docs.keydb.dev/) | An in-memory data store used by millions of developers as a database, cache, streaming engine, and message broker. | [Link](services/keydb.md) |
| [LabelStudio](https://labelstud.io/) | Label Studio is an open source data labeling tool that supports multiple projects, users, and data types in one platform | [Link](services/labelstudio.md) |
| [Lago](https://www.getlago.com/) | Open-source metering and usage-based billing | [Link](services/lago.md) |
| [languageTool](https://languagetool.org/) | An open source online grammar, style and spell checker | [Link](services/languagetool.md) |
| [linkding](https://github.com/sissbruecker/linkding/) | Bookmark manager designed to be minimal and fast. | [Link](services/linkding.md) |
| [listmonk](https://listmonk.app) | Self-hosted newsletter and mailing list manager. | [Link](services/listmonk.md) |
| [MariaDB](https://mariadb.org/) | A powerful, open source object-relational database system | [Link](services/mariadb.md) |
| [Matomo](https://matomo.org/) | Free and open source web analytics platform | [Link](services/matomo.md) |
| [Matrix Rooms Search API](https://github.com/etkecc/mrs) | A fully-featured, standalone, matrix rooms search service. | [Link](services/mrs.md) |
| [Matterbridge](https://github.com/42wim/matterbridge) | Bridges Messenger Chatrooms | [Link](services/matterbridge.md) |
| [Minecraft](https://docker-minecraft-server.readthedocs.io) | The popular voxel-based sandbox game | [Link](services/minecraft.md) |
| [Miniflux](https://miniflux.app/) | Minimalist and opinionated feed reader. | [Link](services/miniflux.md) |
| [Mobilizon](https://joinmobilizon.org/en/) | An ActivityPub/Fediverse server to create and share events. | [Link](services/mobilizon.md) |
| [MongoDB](https://www.mongodb.com/) | A source-available cross-platform document-oriented (NoSQL) database program. | [Link](services/mongodb.md) |
| [Mosquitto](https://mosquitto.org/) | An open-source MQTT broker | [Link](services/mosquitto.md) |
| [n8n](https://n8n.io/) | Workflow automation for technical people. | [Link](services/n8n.md) |
| [Navidrome](https://www.navidrome.org/) | [Subsonic-API](http://www.subsonic.org/pages/api.jsp) compatible music server | [Link](services/navidrome.md)
| [Neko](https://neko.m1k1o.net/) | A self-hosted virtual browser or even desktop environment | [Link](services/neko.md) |
| [NetBox](https://docs.netbox.dev/en/stable/) | Web application that provides [IP address management (IPAM)](https://en.wikipedia.org/wiki/IP_address_management) and [data center infrastructure management (DCIM)](https://en.wikipedia.org/wiki/Data_center_management#Data_center_infrastructure_management) functionality | [Link](services/netbox.md) |
| [Nextcloud](https://nextcloud.com/) | The most popular self-hosted collaboration solution for tens of millions of users at thousands of organizations across the globe. | [Link](services/nextcloud.md) |
| [Notfellchen](https://codeberg.org/moanos/notfellchen) | Self-hosted tool to list animals available for adoption to increase their chance of finding a forever-home | [Link](services/notfellchen.md) |
| [ntfy](https://ntfy.sh/) | Simple HTTP-based pub-sub notification service to send you push notifications from any computer, using simple HTTP PUT or POST requests. | [Link](services/ntfy.md) |
| [OAuth2-Proxy](https://oauth2-proxy.github.io/oauth2-proxy/) | A reverse proxy and static file server that provides authentication using OpenID Connect Providers (Google, GitHub, [Keycloak](services/keycloak.md), and others) to SSO-protect services which do not support SSO natively. | [Link](services/oauth2-proxy.md) |
| [Outline](https://www.getoutline.com/) | An open-source knowledge base for growing teams. | [Link](services/outline.md) |
| [Overseerr](https://overseerr.dev/) | A request management and media discovery tool for the Plex ecosystem | [Link](services/overseerr.md) |
| [Owncast](https://owncast.online/) | Owncast is a free and open source live video and web chat server for use with existing popular broadcasting software. | [Link](services/owncast.md) |
| [OxiTraffic](https://codeberg.org/mo8it/oxitraffic) | [OxiTraffic](https://codeberg.org/mo8it/oxitraffic) is a self-hosted, simple and privacy respecting website traffic tracker. | [Link](services/oxitraffic.md) |
| [Paperless-ngx](https://paperless-ngx.com) | [Paperless-ngx](https://paperless-ngx.com) is a community-supported open-source document management system that transforms your physical documents into a searchable online archive so you can keep, well, less paper. | [Link](services/paperless-ngx.md) |
| [PeerTube](https://joinpeertube.org/) | A tool for sharing online videos | [Link](services/peertube.md) |
| [Plausible Analytics](https://plausible.io/) | Intuitive, lightweight and open source web analytics | [Link](services/plausible.md) |
| [Plex](https://www.plex.tv/) | A personal media server | [Link](services/plex.md) |
| [Postgis](https://postgis.net/) | A spatial database extender for PostgreSQL object-relational database | [Link](services/postgis.md) |
| [Postgres](https://www.postgresql.org) | A powerful, open source object-relational database system | [Link](services/postgres.md) |
| [Postgres Backup](https://github.com/prodrigestivill/docker-postgres-backup-local) | A solution for backing up PostgreSQL to local filesystem with periodic backups. | [Link](services/postgres-backup.md) |
| [PrivateBin](https://privatebin.info/) | Minimalist, open source online pastebin where the server has zero knowledge of pasted data. | [Link](services/privatebin.md) |
| [Prometheus](https://prometheus.io/) | A metrics collection and alerting monitoring solution | [Link](services/prometheus.md) |
| [Prometheus Blackbox Exporter](https://github.com/prometheus/blackbox_exporter) | Blackbox probing of HTTP/HTTPS/DNS/TCP/ICMP and gRPC endpoints | [Link](services/prometheus-blackbox-exporter.md) |
| [Prometheus Node Exporter](https://github.com/prometheus/node_exporter) | Exporter for machine metrics | [Link](services/prometheus-node-exporter.md) |
| [Prometheus Postgres Exporter](https://github.com/prometheus-community/postgres_exporter) | A PostgreSQL metric exporter for Prometheus | [Link](services/prometheus-postgres-exporter.md) |
| [Prometheus SSH Exporter](https://github.com/treydock/ssh_exporter) | SSH probes | [Link](services/prometheus-ssh-exporter.md) |
| [Promtail](https://grafana.com/docs/loki/latest/send-data/promtail/) | An agent which ships the contents of local logs to a private [Grafana Loki](services/grafana-loki.md) instance | [Link](services/promtail.md) |
| [qBittorrent](https://www.qbittorrent.org/) | A BitTorrent client written in native C++ | [Link](services/qbittorrent.md) |
| [Radarr](https://radarr.video/) | A movie organizer/manager for usenet and torrent users | [Link](services/radarr.md) |
| [Radicale](https://radicale.org/) | A Free and Open-Source CalDAV and CardDAV Server (solution for hosting contacts and calendars) | [Link](services/radicale.md) |
| [ReactFlux](https://github.com/electh/ReactFlux) | Third-party web frontend for Miniflux | [Link](services/reactflux.md) |
| [Readeck](https://readeck.org) | A bookmark manager and a read-later tool combined in one. | [Link](services/readeck.md) |
| [Redis](https://redis.io/) | An in-memory data store used by millions of developers as a database, cache, streaming engine, and message broker. | [Link](services/redis.md) |
| [Redlib](https://github.com/redlib-org/redlib) | Browse Reddit without exposing your IP address, browsing habits, and other browser fingerprinting data to the website. | [Link](services/redlib.md) |
| [Redmine](https://redmine.org/) | A flexible project management web application. | [Link](services/redmine.md) |
| [Roundcube](https://roundcube.net/) | A browser-based multilingual IMAP client with an application-like user interface | [Link](services/roundcube.md) |
| [rumqttd](https://github.com/bytebeamio/rumqtt) | A high performance, embeddable [MQTT](https://en.wikipedia.org/wiki/MQTT) broker | [Link](services/rumqttd.md) |
| [SearXNG](https://github.com/searxng/searxng) | A privacy-respecting, hackable [metasearch engine](https://en.wikipedia.org/wiki/Metasearch_engine) | [Link](services/searxng.md) |
| [Semaphore](https://www.ansible-semaphore.com/) | A responsive web UI for running Ansible playbooks | [Link](services/semaphore.md) |
| [Send](https://github.com/timvisee/send) | Fork of Mozilla's [Firefox Send](https://github.com/mozilla/send) which allows you to send encrypted files to other users | [Link](services/send.md) |
| [Soft Serve](https://github.com/charmbracelet/soft-serve) | A tasty, self-hostable [Git](https://git-scm.com/) server for the command line | [Link](services/soft-serve.md) |
| [Sonarr](https://sonarr.tv/) | A smart PVR for newsgroup and bittorrent users | [Link](services/sonarr.md) |
| [Stirling PDF](https://github.com/Stirling-Tools/Stirling-PDF) | A self-hosted PDF converter | [Link](services/stirling-pdf.md) |
| [syncstorage-rs](https://github.com/mozilla-services/syncstorage-rs) | Mozilla Sync Storage server in Rust, used to power Firefox Sync | [Link](services/syncstorage-rs.md) |
| [Syncthing](https://syncthing.net/) | A continuous file synchronization program which synchronizes files between two or more computers in real time | [Link](services/syncthing.md) |
| [Tandoor](https://docs.tandoor.dev/) | The recipe manager that allows you to manage your ever growing collection of digital recipes.| [Link](services/tandoor.md)
| [Telegraf](https://www.influxdata.com/time-series-platform/telegraf/) | An open source server agent to help you collect metrics from your stacks, sensors, and systems. | [Link](services/telegraf.md) |
| [Traefik](https://doc.traefik.io/traefik/) | A container-aware reverse-proxy server | [Link](services/traefik.md) |
| [TSDProxy](https://almeidapaulopt.github.io/tsdproxy/) | A proxy for virtual services in Tailscale | [Link](services/tsdproxy.md) |
| [Uptime Kuma](https://uptime.kuma.pet/) | A fancy self-hosted monitoring tool | [Link](services/uptime-kuma.md) |
| [Valkey](https://valkey.io/) | A flexible distributed key-value datastore that is optimized for caching and other realtime workloads. | [Link](services/valkey.md) |
| [Vaultwarden](https://github.com/dani-garcia/vaultwarden) | A lightweight unofficial and compatible implementation of the [Bitwarden](https://bitwarden.com/)password manager | [Link](services/vaultwarden.md) |
| [Versatiles](https://versatiles.org) | A free stack for generating and serving vector tiles from OpenStreetMap. | [Link](services/versatiles.md) |
| [Wetty](https://github.com/butlerx/wetty) | An SSH terminal over HTTP/HTTPS | [Link](services/wetty.md) |
| [WireGuard Easy](https://github.com/wg-easy/wg-easy) | The easiest way to run [WireGuard](https://www.wireguard.com/) VPN + Web-based Admin UI. | [Link](services/wg-easy.md) |
| [Woodpecker CI](https://woodpecker-ci.org/) | A simple Continuous Integration (CI) engine with great extensibility. | [Link](services/woodpecker-ci.md) |
| [WordPress](https://wordpress.org/) | A widley used open source web content management system | [Link](services/wordpress.md) |
| [Writefreely](https://writefreely.org) | A clean, minimalist publishing platform made for writers with optional federation via ActivityPub. | [Link](services/writefreely.md) |
| [YaCy](https://yacy.net) | Distributed web search engine on a P2P network | [Link](services/yacy.md) |
| [YOURLS](https://yourls.org) | Your Own URL Shortener, on your server | [Link](services/yourls.md) |
| System-related | A collection of various system-related components | [Link](services/system.md) |


## Related playbooks

- [matrix-docker-ansible-deploy (MDAD)](https://github.com/spantaleev/matrix-docker-ansible-deploy) — for deploying a fully-featured [Matrix](https://matrix.org) homeserver. This playbook will remain independent, because the Matrix ecosystem is incredibly large — lots of bots, bridges and other pieces of software. It deserves its own dedicated playbook.

  The basic steps to configure the MDAD playbook and use it to install services are pretty same as doing so with the MASH playbook: **setting up prerequisites (if running this playbook on a different computer), retrieving the MDAD playbook, configuring it as well as the DNS records, and installing the services on the server**. If you have been accustomed to use the MASH playbook, it should not be difficult to set up and use this playbook too.
