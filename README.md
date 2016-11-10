CentOS 7 Install NTP Server

1> yum install ansible -y

2> cd /etc/ansible/
   git clone https://github.com/dongci/ntp-ansible.git

3> Edite hosts

4> mv site.yml.example site.yml

5> Read ./roles/ntp/README.md  &&  Set the key in vars/main

Thank you !!
