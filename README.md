# Glance terminal

Glance terminal is a sub app of Glance.

It's implement a ssh server and a web terminal server, 

User can connect them except glance openssh server and connect.py 
pre version.


## Install

    $ git clone https://github.com/ahhqlrg/coco.git

## Setting

You need update config.py settings as you need, Be aware of: 

*YOU MUST SET SOME CONFIG THAT CONFIG POINT*

They are:

    NAME:
    GLANCE_URL:
    SECRET_KEY:

Also some config you need kown:
    SSH_HOST:
    SSH_PORT:


## Start

    # python run_server.py

When your start ssh server, It will register with glance api,

Then you need login glance with admin user, active it in <Terminal>
 
 If all done, your can use your ssh tools connect it.
 
ssh user@host:port

