# robot-framework-workshop
Workshop material for open kitchen / TestWorksConf

# Creating a new box from the MASTER branch and place contents on USB
1. make sure you documented al manual changes made in the VM in the Vagrantfile. Automate all the things
2. destroy and re-provision the VM. Make sure you test everything

  ```   
  vagrant destroy
  vagrant up
  ```
3. Test provisioing of the VM. Is everything the way you want it?
4. Shutdown VM and create a new box

  ```
  vagrant package --output robot-framework.box
  ```
5. Place Vagrantfile from RELEASE-BOX branch and the vagrant box you just created on USB
6. 
