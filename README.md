# XRAY WS
```
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

```
cat >/root/domain <<EOF
domain.xyz
EOF
```

```
mkdir -p /etc/xray
cat >/etc/xray/domain <<EOF
domain.xyz
EOF
```

```
wget https://raw.githubusercontent.com/solehpolysas/XRAY-WS/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
