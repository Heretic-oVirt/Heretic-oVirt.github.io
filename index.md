## Welcome to the Heretic oVirt Project

These pages act as a Github-based counterpart to the [official project site](https://dangerous.ovirt.life/) of the Heretic oVirt Project (HVP) in order to minimally guide those starting in HVP from here.

### Foreword about the Heretic oVirt Project

The Heretic oVirt Project makes use of the FOSS technologies cited below and in related docs/sites by fully adhering to their respective licenses of use without implying any affiliation or endorsement by their projects nor by the enterprise entities sponsoring them.

# Heretic oVirt Project basic info

The Heretic oVirt Project aims at creating a fully automated [SDDC](https://en.wikipedia.org/wiki/Software-defined_data_center) solution using [CentOS](https://www.centos.org/), [oVirt](https://www.ovirt.org/), [OVN](http://openvswitch.org/support/dist-docs/ovn-architecture.7.html), [GlusterFS](https://www.gluster.org/), [CTDB](https://ctdb.samba.org/), [Samba](https://www.samba.org/), [NFS-Ganesha](https://github.com/nfs-ganesha/nfs-ganesha/wiki) and [Gluster-Block](https://github.com/gluster/gluster-block).

## Installation and usage

A QuickStart document will be put together and published soon.
In the meanwhile, please read the [Overview](https://github.com/Heretic-oVirt/docs/blob/master/Overview-eng.md) document then follow this basic list:

1. Install the PC/VD support machine from the Internet (using [its Kickstart](https://github.com/Heretic-oVirt/kickstart/blob/master/heresiarch.ks)): you only need a CentOS7 x86_64 NetInstall CD or full DVD
2. Install the servers (using [their own Kickstart](https://github.com/Heretic-oVirt/kickstart/blob/master/heretic-host.ks)) from the PC/VD support machine: you don't need anything else, just connect the servers correctly and make them boot from network
3. Launch the Ansible global playbook (which you can familiarize with [here](https://github.com/Heretic-oVirt/ansible/blob/master/hvp/site.yaml)) from the PC/VD support machine: login on the graphical desktop, open a Terminal, become root and run the playbook

## Main repositories

- [Kickstarts for basic infrastructure machines](https://github.com/Heretic-oVirt/kickstart)
- [Ansible code for further infrastructure automation](https://github.com/Heretic-oVirt/ansible)
- [Other kickstart files for guest vms](https://github.com/Heretic-oVirt/other-kickstart)
- [Package building/publishing related resources](https://github.com/Heretic-oVirt/packages)
- [Project documentation](https://github.com/Heretic-oVirt/docs)

## Contacts and contributing

Detailed references and addresses will be published soon.

## Licenses

Basically everything we create is released under GPL v2.0

## Credits

The list of contributors (apart from the obvious debt towards the upstream projects cited above) is still being put together: we plan to publish it soon.

