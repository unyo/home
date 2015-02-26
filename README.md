# home

Basic DigitalOcean setup steps

1. Add new server via digitalocean.org, add SSH key, wait for setup to complete
2. Once server has been added, add IPv4/IPv6 address to DNS server (domains.google.com)
3. ssh root@[IP]
4. sudo add-user unyo
5. sudo add-user unyo sudo
6. local> ssh-copy-id unyo@[IP], test login, test sudo
7. sudo vi /root/.ssh/authorized_keys (remove SSH key from root user)
8. sudo vi /etc/ssh/sshd_config (copy sshd_config, todo: non 22 port)
9. sudo apt-get update && sudo apt-get upgrade && sudo apt-get autoremove (update)
10. sudo apt-get install tmux ruby python mercurial git (install basics)
11. (todo: bundler sinatra datamapper, copy over files, setting up ecrypt-fs, setting up tmux, irssi, btsync, thin, nginx, https, init scripts, mysql, optional: tor, optional: bitcoin. eventually: micro, music server, elections.io, *bay) 
12. (todo: zipping old files and copying, cloning repos)
