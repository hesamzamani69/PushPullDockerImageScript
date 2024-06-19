# PushPullDockerImageScript
To use the script, in the same directory create two files:
  1- image.list
  2-image.list.old
Then place the required image URL (following your private registry URL naming pattern) and then run the script.

Note:
1- Before running the script, create two DNS records for your old and new Nexus registry in your DNS server or /etc/hosts. the first DNS records points to the old registry and the second addresses the new Nexus registry.
