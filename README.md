# maas_ansible

Ansible Playbook to deploy Canonical MAAS 2.1+, Ansible 2.2 was used. Currently this deployment does not provide MAAS High Availability (HA) functionality, it may be available in the near future.

Running this playbook will result  in the  following:

* Deploying MAAS
* Add the required bridges and VLAN interfaces
* SSH key configuration
* Set MAAS common Settings (upstream DNS, NTP servers, default storage layout and network discovery)


DHCP, Fabrics and Spaces  are not going to be configured here, this [script](https://github.com/hamzaachi/maas_scripts) can be used to do so, in addition to other nodes configuration.
