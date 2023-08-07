# Qemu-patched-git
Change cpu_speed on line 119 to the number that comes out when you run this:  
`sudo dmidecode | grep "Current Speed:" | cut -d" " -f3`