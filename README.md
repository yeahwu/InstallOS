# InstallOS

DD Linux systems on VPS with support for Debian 9, 10 and Ubuntu 18.04, 20.04.

Partitioned /boot, /swap, and root partitions. The partition /boot is 160MB, swap partition is 1 times the memory, and the rest is allocated to the root partition.

Installed the common software 'wget curl git vim net-tools'. Some other simple system settings.

Download and run the DD script:

`wget https://raw.githubusercontent.com/yeahwu/InstallOS/main/InstallOS.sh && bash InstallOS.sh`

Default root password: `111111.online`
