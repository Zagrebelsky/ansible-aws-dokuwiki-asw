# ansible-aws-dokuwiki-asw
Ansible role create AWS Linux 2 instace and deploy dockuwiki and Telegram proxy

Vars:
|Var name|Default|Description|
---------|-------|-----------
|secret|telegram_secret|Telegram proxy secret|
|data_dir|/var/docker/MTPproxy/data|Path to telegram data dir|
|telegram_port|4443|Telegram port|
|wiki_host|my_wiki.com|nginx hostname\ip address|
|docker_dir|/var/docker|path to nginx and dokuwiki files|