# Ansible role for fast SSH tunnels deployment

Sample dict with settings for role:

```
ssh_tunnels:
  TUNNEL1_CH:
    SSH_TUNNEL_LOCAL_HOST: "127.0.0.1"
    SSH_TUNNEL_LOCAL_PORT: 8123
    SSH_TUNNEL_REMOTE_HOST: "15.21.63.13"
    SSH_TUNNEL_REMOTE_HOST_FINGERPRINT: "15.21.63.13 ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyAAAAIbmlzdHAyNTYAAABBBAFwf2j/TbX/BfXtGEz6HSxuDktm/7mWYvj0ajj4Q/haR68GSlk9/7Yk/V+s2paxvrwnhuYjGOPxUtQq99nOxZo="
    SSH_TUNNEL_REMOTE_PORT: 8123
    SSH_TUNNEL_KEY: "/root/.ssh/interserver.pem"

  TUNNEL2_PG:
    SSH_TUNNEL_LOCAL_HOST: "127.0.0.1"
    SSH_TUNNEL_LOCAL_PORT: 5432
    SSH_TUNNEL_REMOTE_HOST: "15.21.63.13"
    SSH_TUNNEL_REMOTE_HOST_FINGERPRINT: "15.21.63.13 ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyAAAAIbmlzdHAyNTYAAABBBAFwf2j/TbX/BfXtGEz6HSxuDktm/7mWYvj0ajj4Q/haR68GSlk9/7Yk/V+s2paxvrwnhuYjGOPxUtQq99nOxZo="
    SSH_TUNNEL_REMOTE_PORT: 5432
    SSH_TUNNEL_KEY: "/root/.ssh/interserver.pem"
```
