weechat-extras
---

This is a meta git repository that provides package repositories for the weechat-extras packages

To use this repository:

**Debian**

```bash
apt install apt-transport-https
cat << EOF >> /etc/apt/sources.list
deb https://raw.githubusercontent.com/bqv/weechat-extras/master/debian wheezy main
EOF
apt update
apt install weechat-slack
```
