# holbertonschool-network

Networking projects: answer files and Bash scripts.

## basics_0 (Networking basics #0)

| File | Description |
|------|-------------|
| `0-OSI_model` | Answers: the OSI model |
| `1-types_of_network` | Answers: LAN, WAN and Internet |
| `2-MAC_and_IP_address` | Answers: MAC and IP addresses |
| `3-UDP_and_TCP` | Answers: UDP and TCP |
| `4-TCP_and_UDP_ports` | Bash script that displays listening sockets with PID and program name |
| `5-is_the_host_on_the_network` | Bash script that pings an IP address 5 times |

## basics_1 (Networking basics #1)

| File | Description |
|------|-------------|
| `0-change_your_home_IP` | Bash script that makes localhost resolve to 127.0.0.2 and facebook.com to 8.8.8.8 |
| `1-show_attached_IPs` | Bash script that displays all active IPv4 IPs of the machine |
| `2-port_listening_on_localhost` | Bash script that listens on port 98 on localhost |

## Usage

```
sudo ./basics_0/4-TCP_and_UDP_ports
./basics_0/5-is_the_host_on_the_network 8.8.8.8
sudo ./basics_1/0-change_your_home_IP
./basics_1/1-show_attached_IPs
sudo ./basics_1/2-port_listening_on_localhost
```

Warning: `0-change_your_home_IP` edits `/etc/hosts`. Revert `localhost` to
`127.0.0.1` if you run it on a machine you keep using.
