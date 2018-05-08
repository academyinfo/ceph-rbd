# Install ceph-rbd

# pour télécharger l'image de rbd et l'installer sur CoreOS suivez simplement les commandes suivantes :

sudo git clone https://github.com/amineerroutbi-nplusone/ceph-rbd \
cd ceph-rbd \
sudo mkdir -p /opt/bin \
sudo cp -r rbd /opt/bin \
cd /opt/bin \
sudo chmod +x rbd \
rbd #run command to download ceph images. \
Unable to find image 'ceph/base:latest' locally \
latest: Pulling from ceph/base \
... \
exit \
