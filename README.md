Schibsted.Monit
=====

Installes and configures monit to run its HTTP server.

Requirements
------------
Ubuntu/Debian

Role Variables
--------------
```
monit_cycle:
  How often should monit poll for event from monitored services?
  Default: 30 secs

```

Dependencies
------------
None


Example Playbook
-------------------------

```
---
host: monit
roles: 
 - Schibsted.monit
```

License
-------

MIT

Author Information
------------------

* Erlend Hamnaberg (github.com/hamnis, twitter.com/hamnis)
* Jordi Arnavat (github.com/acjzz, twitter.com/acjzz)

