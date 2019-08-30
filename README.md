Packer CentOS template
==============

Packer and vagrant to create my worker, centos 7.6 build 1810

Building with Packer for Local Usage
--------------

Baking:
```bash
$ make last

$ packer build -var-file vars/centos-7.6.1810.json vagrant-centos-local.json
```

Local Import:
```bash
$ vagrant box add 'sbeliakou/centos-7.6-x86_64-minimal' sbeliakou-vagrant-centos-7.6-x86_64-minimal.box
```

