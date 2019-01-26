# Ruby on Rails development deploy

## For create ruby on rails project on your PC

1.Please install virtualbox on your device.   
--
<https://www.virtualbox.org/>  

2.Please install vagrant on your device.  
--
<https://www.vagrantup.com/downloads.html>  
(select your device's package)

3.Edit your file  
--
rails_base/vagrantconfig.local.rb  
(this file is overwrite on your enviroment file.)  
rails_base/provisioning/roles/deploy/main.yml  

4.Input this command.  
--
`$ vagrant up`  
`$ vagrant ssh`
