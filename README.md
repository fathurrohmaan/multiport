# multiport
Fathur Rohman


rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget -q https://raw.githubusercontent.com/Friendz99/multiport/main/setup.sh && chmod +x setup.sh && ./setup.sh && rm -f setup.sh
