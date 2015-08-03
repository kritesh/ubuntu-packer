# ubuntu-packer
ubuntu-14-04-x64-virtualbox.box with vagrant and packer on windows

What are tools we need to get started ?

1) packer installed on windows
2) vagrant installed on windows
3) virtualbox installed on windows
4) ubuntu-14.04.2-server-amd64.iso  --> Download it from ubnutu site


How it works ?

packer looks for a json file. This josn file has a specific format. Sample josn file which we are going to use is: template.json

We also need a kickstart file which will automate all the tasks in ubuntu installation. Our kickstart file here is pressed.cfg

#### Command to run from windows command prompt:

### packer build template.json


### challenges which we may face:

1) enable virtulaiztion in your windows installation. Go to IT team to enable virtualization or do it yourself.



#### This is raw document and will be updated later.






