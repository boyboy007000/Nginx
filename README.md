# Nginx
#step 1: install rtorent and nginx and rutorrent
sudo bash -c "$(wget --no-check-certificate -qO - https://raw.githubusercontent.com/arakasi72/rtinst/master/rtsetup)"
rtinst
# step 2 install deluge and qbitorrent
git clone https://github.com/htpcBeginner/AtoMiC-ToolKit /opt/AtoMiC-ToolKit
 cd /AtoMiC-ToolKit
 sudo bash setup.sh
 # step 3 edit nginx defau
  cd /etc/nginx/
   nano sites-enabled/default
   
