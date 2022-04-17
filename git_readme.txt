sudo dpkg -P $(dpkg -l | grep nvidia-driver | awk '{print $2}')
sudo apt autoremove

sudo apt install xserver-xorg-video-nouveau



sudo bash NVIDIA-Linux-x86_64-XXX.XX.run --uninstall

sudo nvidia-xconfig --restore-original-backup

sudo rm /etc/modprobe.d/blacklist-nvidia-nouveau.conf



###############################################################

sudo apt update && sudo apt upgrade -y

sudo whoami -> root

su

ubuntu-drivers devices

sudo ubuntu-drivers autoinstall
ou
sudo apt install nvidia-driver-460

nvidia-smi


CTRL+ALT+F1
sudo /etc/init.d/gdm stop 


