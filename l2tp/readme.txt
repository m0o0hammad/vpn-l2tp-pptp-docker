

###############################load module#########################
sudo modprobe af_key

###########################forwarding ipv4###################
sysctl -w net.ipv4.ip_forward=1
