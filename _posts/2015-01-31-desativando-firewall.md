---
layout: post
title: Desativando o firewall no Oracle Linux
---

Como root, execute os seguintes comandos:

Para IPV4:

<div class="message">
- service iptables save

- service iptables stop

- chkconfig iptables off
</div>


Para IPV6:

<div class="message">
- service ip6tables save
- service ip6tables stop
- chkconfig ip6tables off
</div>
