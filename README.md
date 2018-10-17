# server_start

Ubuntu 16.04 server setup script - updates system, installs apache2, and gets https through EFF cerbot, hardens server, mod-security (has files from for mod-security rules https://github.com/SpiderLabs/owasp-modsecurity-crs)

If your username is not "ubuntu" you will have to edit .conf files

# install
  $ git clone https://github.com/mis0b1gboy/server_start.git
  
  $ cd server_start
  
  $ chmod +x start.sh
  
  $ ./start.sh

Or if your lazy just use this one liner ;) - git clone https://github.com/mis0b1gboy/server_start.git && cd server_start && chmod +x start.sh && bash start.sh
