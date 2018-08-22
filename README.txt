Install virtualbox:
$sudo apt-get install virtualbox

Install vagrant:
$sudo apt-get install vagrant

Create a dir for the project:
$mkdir milter
$cd milter

Run:
$vagrant init hashicorp/precise64
$vagrant up

SSH to the VM:
$vagrant ssh

BELOW THIS LINE ALL COMMANDS ARE IN THE VM:
Install sendmail:
$sudo apt-get install sendmail






