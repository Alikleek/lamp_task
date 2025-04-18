LAMP stack role
=========

to install and configure LAMP stack elements (apache2 , mysql, php)


Example Playbook
----------------

to run the playbook use the following command
$ ansible-playbook playbook.yaml -i inventory --ask-vault-pass

##for vault password please contact author

License
-------

BSD

running
-------

the role itself contain a main.yml task file which has the include option depending on different os family, due to difference in service and packages manager between debian and redhat distros

an index file can be found in the templates folder where you can test the apache server and the php script processor



Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
