---
layout: post
title: Desativando o firewall no Oracle Linux
---

Como root, execute os seguintes comandos:

Para IPV4:

service iptables save

service iptables stop

chkconfig iptables off

Para IPV6:

service ip6tables save

service ip6tables stop

chkconfig ip6tables off
