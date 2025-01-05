# ludus_role
Some ansible role for ludus.cloud
Check https://docs.ludus.cloud/

template from : https://github.com/badsectorlabs/ludus_ansible_role_template

## ludus_aurora_agent

Check https://github.com/frack113/ludus_aurora_agent

## ludus_graylog_server

You need to log to the ubuntu and check `/var/log/graylog-server/server.log`
There is a temporal password to configure your instance...

```
                                                             ---
                                                             ---
                                                             ---
    ########  ###   ######### ##########   ####         #### ---         .----               ----
  ###############   ###################### #####       ####  ---      ------------       .----------- --
 #####     ######   #####              #### ####      ####   ---     ---        ---     ---        -----
####         ####   ####       ############  ####     ####   ---    --           ---   ---           ---
###           ###   ####     ##############   ####   ####    ---   ---            --   --             --
####         ####   ####    ####       ####    #### ####     ---   ---            --   --            .--
#####       #####   ####    ####       ####     #######      ---    ---          ---   ---           ---
 ################   ####     ##############     ######-       --     ----      ----      ---       -----
   ##############   ####      #############      #####        -----   -----------         ----------  --
             ####                                ####                                                ---
#####       ####                                ####                                     -          .--
  #############                                ####                                     -----     ----
     ######                                   ####                                          -------

========================================================================================================

It seems you are starting Graylog for the first time. To set up a fresh install, a setup interface has
been started. You must log in to it to perform the initial configuration and continue.

Initial configuration is accessible at 0.0.0.0:9000, with username 'admin' and password 'xjYZzgphjt'.
Try clicking on http://admin:xjYZzgphjt@0.0.0.0:9000

========================================================================================================
```

## ludus_caldera_server

Install Caldera 5.x main branch on an linux server

Tests:

[ ] AlmaLinux 9
[x] Ubuntu 22.04
[X] Ubuntu 24.04

## ludus_caldera_client

Install sandcat agent on a windows client

## Next

![img](./freepik.jpeg)