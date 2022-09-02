CentOS




80/tcp  open  http     syn-ack ttl 63 Apache httpd 2.4.37 ((centos) OpenSSL/1.1.1k mod_fcgid/2.3.9)
[    web users : jan, prisonmike, nick, creed
]    
    wp users (confirmed): prisonmike, nick
    brute force http://office.paper/wp-login.php
        nick - xato 1000
        prisonmike - xato 1000

    WordPress version 5.2.3
        WordPress Core < 5.2.3 - Viewing Unauthenticated/Password/Private Posts           | multiple/webapps/47690.md       
        WordPress Core 5.2.3 - Cross-Site Host Modification | php/webapps/47361.pl      
        Wordpress Core 5.2.2 - 'post previews' XSS | php/webapps/49338.txt                 
    theme : construction-techup 1.1
        x
    stops-core-theme-and-plugin-updates 9.0.9  
        x

    http:/office.paper/wp-content/uploads/

    http://office.paper/wp-content/uploads/2021/07/ 08 09 


443/tcp open  ssl/http syn-ack ttl 63 Apache httpd 2.4.37 ((centos) OpenSSL/1.1.1k mod_fcgid/2.3.9)









22/tcp  open  ssh      syn-ack ttl 63 OpenSSH 8.0 (protocol 2.0)  



ON BOX:
user : dwight
bad chars: ;,`,&,$,0x0a,\n,*,?,|,[,{,(,,\,\\,>,<,',%



PRIV
New path exported: /home/dwight/.local/bin:/home/dwight/bin:/home/dwight/.local/bin:/home/dwight/bin:/home/dwight/hubot/node_modules/coffeescript/bin:node_modules/.bin:node_modules/hubot/node_modules/.bin:/usr/bin:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/sbin

