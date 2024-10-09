Copy and paste both folders into etc then rebuild initramfs and do

sudo udevadm control --reload-rules
sudo udevadm trigger
