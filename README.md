# centos8 packer vshere 

This creates a vmware vshere virtual machine centos [kickstartfile](http/ks_test.cfg) should also work for centos7.

Add new password in [packerfile](packer.json) and kickstartfile also change public key at the end of kickstartfile

Some adjustments should be made in [ansible-playbook](server-lite.yml) since its the packer provisioner
