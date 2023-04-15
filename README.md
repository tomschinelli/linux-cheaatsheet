# Linux Cheatsheet

A collection of some useful linux commands.

| Command  | Description                                           | example                         |
|----------|-------------------------------------------------------|---------------------------------|
| lsof     | Lists open files for running Unix processes           | `lsof /var/log/prog/prog.log`   |
| iptables | administration tool for IPv4 packet filtering and NAT | `iptables -L -v`                |
| strace   | trace system calls and signals                        | `strace docker ps`              |
| tcpdump  | dump traffic on a network                             | `tcpdump -nn lo`                |
| nc       | arbitrary TCP and UDP connections and listens         | `nc -l -p 8080`                 |
| hey      | HTTP load generator, formerly known as rakyll/boom    | `hey -z  http://localhost:8000` |


