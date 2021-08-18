Copying a file to a list of remote hosts
==============================================

#!/bin/bash



for HOST in ubuntu01 fedora02 centos03 rhel06


do


	scp somefile $HOST:/var/tmp/


done