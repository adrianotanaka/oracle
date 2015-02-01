---
layout: post
title: Desativando o firewall no Oracle Linux
---

Como root, execute os seguintes comandos:
<div class="message">
Para IPV4:

service iptables save

service iptables stop

chkconfig iptables off
</div>
<div class="message">
Para IPV6:

service ip6tables save

service ip6tables stop

chkconfig ip6tables off
</div>
