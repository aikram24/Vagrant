Provision Enviorment With puppet Very simple vagrant file with puppet provisioning. We will be installing apache2. So we don't have to manually install and link the /var/www to shared folder /vargrant.

We will be using simple ubuntu box image for this.

/vagrant is share from your host machine. It will be there even you destroy the guest vagrant.

Once you clone this repo. Only commands you will need to run as following:

vagrant up # Will create create a new VM using the Vagrantfile

vagrant ssh # Will ssh into the machine that you just created

If you wants to delete the the newly created VM you can simply do following:

vagrant destroy # Make sure you are in this direcroy when runnig this command.

vagrant box remove precise64 # Will remove the name from the list
