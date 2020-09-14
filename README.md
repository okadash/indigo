# INDIGO-CLI

This is indigo api command line tools for NTTPC indigo platform users.

# USAGE

| command | description |
| --- | --- |
|indigo `init` | initialize access token for new request |
|indigo `apikey list` | list apikey |
|indigo `apikey generate` | generate new apikey |
|indigo `sshkey list [active]` | list sshkey |
|indigo `[instance] create <ssh_key_id> <name> [instancePlan] [os_id]` | start instance |
|indigo `[instance] start <instance_id>` | start instance |
|indigo `[instance] stop <instance_id>` | halt instance |
|indigo `[instance] forcestop <instance_id>` | immediatly poweroff instance |
|indigo `[instance] reset <instance_id>` | reboot instance |
|indigo `[instance] destroy <instance_id>` | destroy instance |
|indigo `firewall create <desc>` | create firewall templates |
|indigo `firewall list` | list firewall templates |
|indigo `firewall get <template_id>` | retrieve firewall template with id |
|indigo `firewall assign <instance_id> <template_id>` | assign firewall template to the instance |
|indigo `firewall delte <template_id>` | delete firewall template with id |
|indigo help` | show help

