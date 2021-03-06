Indigo API command line tools for [WebArena Indigo](https://web.arena.ne.jp/indigo/) platform users.

# Requirement

* [shelib @core](https://github.com/okadash/indigo) >=0.5.0
* jq (tested on 1.5.0)
* gnupg (tested on 2.2.12 )

# INSTALL

Use [shef](https://github.com/okadash/shef) to install indigo-cli:

``` 
shef install https://github.com/okadash/indigo-cli
```

For API access, you need to store API key credential in somewhere, and set CRED_PATH environmental variable in your shrc.

```
echo '{"apiKey":"NskcH3Uw91L2ms8vSao7g3pR8WAqEq6A","apiSecret":"o37Mcaw01KLpkOgT"}' >> ~/your/secret/path
echo 'CRED_PATH=~/your/secret/path >> ~/.bashrc
```

# USAGE

| command | description |
| --- | --- |
|indigo init | initialize access token for new request |
|indigo apikey list | list apikey |
|indigo apikey generate | generate new apikey |
|indigo sshkey list `[active]` | list sshkey |
|indigo create `<sshkey_id>` `<name>` `[plan_id]` `[os_id]` | create instance |
|indigo start `<instance_id>` | start instance |
|indigo stop `<instance_id>` | halt instance |
|indigo forcestop `<instance_id>` | immediatly poweroff instance |
|indigo reset `<instance_id>` | reboot instance |
|indigo destroy `<instance_id>` | destroy instance |
|indigo instance `<desc>` | operate instances <br>`<desc>`: start, stop, forcestop, reset, destroy, types, os, spec |
|indigo firewall create `<desc>` | create firewall templates |
|indigo firewall `list` | list firewall templates |
|indigo firewall get `<template_id>` | retrieve firewall template with id |
|indigo firewall assign `<instance_id>` `<template_id>` | assign firewall template to the instance |
|indigo firewall delte `<template_id>` | delete firewall template with id |
|indigo help | show help

# ABOUT INDIGO API

See WebArena official [API Documentation](https://indigo.arena.ne.jp/userapi/).

# Author

okadas[at]tanban.org
