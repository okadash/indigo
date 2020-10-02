# Unimplemented CLI functions 

* `sshkey create`
* `sshkey update`
* `sshkey destroy`
* `firewall update`
* dns management

# Enhancement

* human readable default output and --full option for whole json output
* optional interactivity
* firewall template file loading
* ~~response caching (with specific TTL)~~
* response pipelining to other functions

# Refactoring

* shelib 0.5.x compatibility
* separate lib/\*/\* library functions to each function files

# BUGS

* `apikey delete` cannot delete other API keys.

