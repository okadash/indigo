# INDIGO-CLI

This is Indigo API command line tools for [WebArena Indigo](https://web.arena.ne.jp/indigo/) platform users.

# INSTALL

Use [shef](https://github.com/okadash/shef) to install indigo-cli:

``` 
shef install https://github.com/okadash/indigo-cli
```

# USAGE

| command | description |
| --- | --- |
|indigo init | initialize access token for new request |
|indigo apikey `list` | list apikey |
|indigo apikey `generate` | generate new apikey |
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

# Contact

indigo-tools@lab.sysnk.net (SyaNaka Lab.)
