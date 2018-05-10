weechat-extras
---

This is a meta git repository that provides package repositories for the weechat-extras packages

To use this repository:

* Debian

```bash
sudo apt-get install apt-transport-https
cat << EOF >> /etc/apt/sources.list
deb https://raw.githubusercontent.com/bqv/weechat-extras/master/debian main
EOF
sudo apt-get update
sudo apt-get install weechat-slack
```
