cloud3rsio.logrotate_rules
=========

Update logrotate rules.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.logrotate_rules
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `logrotate_rules` | Reference to [defaults/main.yml](defaults/main.yml) | Array |

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.logrotate_rules
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
