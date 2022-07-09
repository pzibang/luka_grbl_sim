# luka_grbl_sim

## compile 
>cd grbl-sim
>make new

you must install 'socat' before you execute the simport.sh:
>sudo apt-get install socat –y

execute the simport.sh:
>cd grbl-sim
./simport.sh

use minicom input command:
>minicom  -D  /tmp/ttyFAKE  -b  115200
