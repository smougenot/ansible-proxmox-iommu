Role Name
=========

[![Cotinuous Integration](https://github.com/smougenot/ansible-proxmox-iommu/actions/workflows/ci.yml/badge.svg)](https://github.com/smougenot/ansible-proxmox-iommu/actions/workflows/ci.yml)

Goal is to IOMMU on Proxmox VE.

Requirements
------------

None

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
      - { role: smougenot.proxmox-iommu, tags: iommu }
```

License
-------

MIT

Author Information
------------------
