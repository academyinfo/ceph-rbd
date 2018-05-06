# Install ceph-rbd
sudo git clone https://github.com/academyinfo/ceph-rbd/ \
cd ceph-rbd \
sudo mkdir -p /opt/bin \
sudo cp -r rbd /opt/bin
sudo chmod +x rbd
rbd #run command to download ceph images.
Unable to find image 'ceph/base:latest' locally
latest: Pulling from ceph/base
...
exit
