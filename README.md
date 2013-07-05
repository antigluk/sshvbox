sshvbox
=======

SSH to one of running VMs

  1) On all machines configure NAT Port Forwarding from random port to 22 port (without collisions)

  2) Use sshvbox as

    $ sshvbox
     1) "CentOS 5" {5f877c2e-14a8-4aee-a467-8d9c369b2aec} <52222>
     2) "Hortonworks Sandbox 1.3" {b1a9f101-096f-46ec-87e4-f07211b54126} <2222>
    select> 1
    root@localhost's password: 
    Last login: Fri Jul  5 13:17:58 2013 from 10.0.2.2
    [root@vagrant-centos-5 ~]# logout


Default user is 'root'. You can choose user to connect as first argument.