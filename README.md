#----------------------------------------------------------#
#              Proteção Anti-DDoS: Reforçando              #
#----------------------------------------------------------#


Este script implementa um firewall utilizando o iptables para proteger o servidor associado ao site Cyber Gamers.
Foi desenvolvido pelos autores poweroff e testado contra ataques DDoS pela comunidade.
Mais informações sobre o projeto podem ser encontradas em https://cyber-gamers.org/

Nota: Certifique-se de rever e personalizar as regras do iptables de acordo com os requisitos específicos do
seu ambiente antes de implementar este script em produção.


############ EXTRA STUFF TO HELP HIGH TRAFFIC (DDOS) ##################


###################################################################################################################
# _|___|___|___|___|___|___|___|___|___|___|___|___|                                                             ##
# ___|___|___|___|___|___|___|___|___|___|___|___|__        IPTables: Linux's Main line of Defense               ##
# _|___|___|___|___|___|___|___|___|___|___|___|___|        IPTables: Linux's way of saying no to DoS kids       ##
# ___|___|___|___|___|___|___|___|___|___|___|___|__                                                             ##    
# _|___|___|___|___|___|___|___|___|___|___|___|___|        Version 1.0.0 -                                      ##
# ___|___|___|___|___|___|___|___|___|___|___|___|__        IPTables Script created by p0w3r0ff                  ##
# _|___|___|___|___|___|___|___|___|___|___|___|___|                                                             ##
# ___|___|___|___|___|___|___|___|___|___|___|___|__        Sources used and Studied;                            ##
# _|___|___|___|___|___|___|___|___|___|___|___|___|                                                             ##
# ___|___|___|___|___|___|___|___|___|___|___|___|__     http://ipset.netfilter.org/iptables.man.html            ##
# _|___|___|___|___|___|___|___|___|___|___|___|___|                                                             ##
# ___|___|___|___|___|___|___|___|___|___|___|___|__                                                             ##
###################################################################################################################
