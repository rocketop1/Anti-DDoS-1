#----------------------------------------------------------#
#              Proteção Anti-DDoS: Reforçando              #
#----------------------------------------------------------#


Este script implementa um firewall utilizando o iptables para proteger o servidor associado ao site Cyber Gamers.
Foi desenvolvido pelos autores poweroff e testado contra ataques DDoS pela comunidade.
Mais informações sobre o projeto podem ser encontradas em https://cyber-gamers.org/

Nota: Certifique-se de rever e personalizar as regras do iptables de acordo com os requisitos específicos do
seu ambiente antes de implementar este script em produção.

Fail2Ban Alternativas:
DenyHosts:

Descrição: Bloqueia automaticamente endereços IP de hosts que exibem comportamento suspeito.
Site: DenyHosts
SSHGuard:

Descrição: Monitora logs de serviços como SSH, FTP, etc., e bloqueia IPs maliciosos.
Site: SSHGuard
CSF (ConfigServer Security & Firewall):

Descrição: Oferece uma interface de gerenciamento para iptables e inclui recursos de detecção de intrusões.
Site: CSF
ModSecurity Alternativas:
NAXSI:

Descrição: Um WAF (Web Application Firewall) para Nginx, focado em segurança contra injeções.
Site: NAXSI
Shadow Daemon:

Descrição: Um WAF para web applications baseado em mod_security com foco na simplicidade e eficácia.
Site: Shadow Daemon
iptables Alternativas:
nftables:

Descrição: Substituto moderno para iptables, oferecendo maior flexibilidade.
Site: nftables
ufw (Uncomplicated Firewall):

Descrição: Uma interface de usuário para iptables que facilita a configuração.
Site: ufw
Firewalld:

Descrição: Ferramenta de gerenciamento dinâmico de firewall para sistemas Linux.
Site: Firewalld
Outras Ferramentas de Segurança:
OSSEC:

Descrição: Uma solução de detecção de intrusões que fornece análise de logs, detecção de rootkits, etc.
Site: OSSEC
Snort:

Descrição: Sistema de detecção de intrusões de código aberto (IDS) e sistema de prevenção de intrusões (IPS).
Site: Snort
Suricata:

Descrição: Motor de regras de detecção de intrusões de alta performance.
Site: Suricata
AIDE (Advanced Intrusion Detection Environment):

Descrição: Sistema de monitoramento de integridade de arquivo.
Site: AIDE


Essas ferramentas oferecem uma variedade de recursos para fortalecer a segurança do seu servidor. Lembre-se de adaptar suas escolhas de acordo com os requisitos específicos do seu sistema e suas preferências de configuração.
