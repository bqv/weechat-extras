weechat-extras
---

This is a meta git repository that provides package repositories for the weechat-extras packages.

Your plugins are welcome, contact [bqv](mailto:frony0@gmail.com) to have your packages added.

**Plugins**

* slack.so ([weechat-slack](https://github.com/bqv/weechat-slack))
* ~~discord.so~~ ([weechat-discord](https://github.com/khyperia/weechat-discord):TBP)
* ~~rocketchat.so~~ (TBI)

**Usage**

To use this repository:

*Debian*

```bash
apt install apt-transport-https

cat << EOF >> /etc/apt/sources.list
deb https://raw.githubusercontent.com/bqv/weechat-extras/master/debian wheezy main
deb-src https://raw.githubusercontent.com/bqv/weechat-extras/master/debian wheezy main
EOF

apt-key adv --keyserver pgp.mit.edu --recv-keys 77A31D11

apt update

apt install weechat-slack
```
