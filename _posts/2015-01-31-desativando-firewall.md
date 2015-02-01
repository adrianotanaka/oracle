---
layout: post
title: Desativando o firewall no Oracle Linux
---

Como root, execute os seguintes comandos:

Para IPV4:

<div class="message">
- service iptables save<br>

- service iptables stop<br>

- chkconfig iptables off<br>
</div>


Para IPV6:

<div class="message">
- service ip6tables save<br>
- service ip6tables stop<br>
- chkconfig ip6tables off<br>
</div>
