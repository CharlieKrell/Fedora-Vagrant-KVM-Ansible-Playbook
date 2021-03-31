# Fedora-Vagrant-KVM-Ansible-Playbook
This configures a Fedora server to use Vagrant with the KVM plugin.

If you run into an issue with the [install vagrant's libvirtd plugin] section of the playbook, 
you can manually run 
```CONFIGURE_ARGS="with-libvirt-include=/usr/include/libvirt with-libvirt-lib=/usr/lib64" vagrant plugin install vagrant-libvirt``` 
on the command line
