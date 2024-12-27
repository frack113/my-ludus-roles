# ludus_role
Some ansible role for ludus.cloud
Check https://docs.ludus.cloud/

template from : https://github.com/badsectorlabs/ludus_ansible_role_template

## ludus_aurora_agent
WARNING For aurora you need to have a valid aurora-agent.lic and the aurora-agent.zip

- go here : https://www.nextron-systems.com/aurora/
- save you licence to /ludus_aurora_agent/files/aurora-agent.lic
- Save the agent zip file to /ludus_aurora_agent/files/aurora-agent.zip


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

Install Caldera 5.x main branch on an ubuntu server

## Next

![img](./freepik.jpeg)