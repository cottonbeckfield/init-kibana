# init-kibana

This script runs Kibana4 on RHEL6 / CENTOS6 as a non-root user.
You can specify the user you wish to run Kibana4 as.

To make this script work, you'll need to change the following;

Location of Kibana bin file:

```
KIBANA_BIN=/home/kibana_user/kibana/current/bin
```

```
DAEMON_USER=kibana_user
```
Once that's finished, you'll install the script to /etc/init.d/kibana
