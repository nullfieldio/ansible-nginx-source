Nginx_source
=========

Installs nginx from source based on version.


Role Variables
--------------
* "nginx_prefix" Install location of nginx
* "nginx_version" version you want to install
* "nginx_src_dir" directory to use for building nginx
* "nginx_conf" config file you want to point nginx at

Example Playbook
----------------
   hosts: all 
    roles:
    - role: nginx_source
      nginx_prefix: /home/nginx # Install location of nginx
      nginx_version: 1.8.0
      nginx_src_dir: "/home/src/"
      nginx_conf: /home/application/nginx/nginx.conf


License
-------

BSD

