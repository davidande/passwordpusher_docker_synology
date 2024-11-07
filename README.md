# PasswordPusher_Docker_Synology

This project helps You installing https://pwpush.com/ solution on a Synology NAS though Container Manager

This configuration includes all Community fonctionnalities: Password, Files, urls, Admin dashboard
![image](https://github.com/user-attachments/assets/6326daf6-29d7-4eda-b2a3-8cd4b57d5ae6)


Create /volume1/docker/passwordpusher

Create /volume1/docker/passwordpusher/db

Create /volume1/docker/passwordpusher/storage

create a project into container manager

use yaml_config as yaml file

fill free to change passwords and usernames for more security

create

Configure the reverse proxy on Your NAS matching PWP__HOST_DOMAIN (this is usefull only if You need to use PasswordPusher from Your LAN and the WAN

done

For more customization https://docs.pwpush.com/docs/self-hosted-configuration/



use your prefered gateway to get https acces (CloudFlare....)

otherwise use reverse proxy on your nas

For the admin console configuration: https://docs.pwpush.com/docs/admin-dashboard/

Based on: https://mariushosting.com/how-to-install-password-pusher-on-your-synology-nas/
