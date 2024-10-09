Copy and paste both folders into etc then rebuild initramfs and do

sudo udevadm control --reload-rules
sudo udevadm trigger

This may or may not help with EDL just a way of easy tracking.
