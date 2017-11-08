# scriptubuntuROS
How to use the scripts

To use the scripts:

Make the user a member of the group "dialout" (this only has to be done once):

Open a terminal and enter the following command:

  $ sudo usermod -a -G dialout $USER
  
Logout and login again (the change is only made after a new login).

Download the desired script

Run the script in a bash shell (e.g. to run ubuntu_sim.sh):

  $ source ubuntu_skyrats.sh
