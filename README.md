# Arch Bootstrap Script

**THIS PROJECT IS NOT DONE YET**

My personal scripts for bootstraping a archlinux system.  
Not designed to be very flexible.

# Usage
1. Boot a computer with arch live image.
2. Prepare the partitions for installing the system.
3. Make sure the internet is available.
4. run the following command:
```console
$ curl https://raw.githubusercontent.com/leomao/arch-bootstrap/master/bootstrap.sh -o bootstrap.sh
$ vim bootstrap.sh # set the variables to what you need.
$ vim chroot.sh # set the variables to what you need.
$ bash bootstrap.sh
```
