# kafkamonpy
A small kafka offset monitor written using kafka client along the lines of stormkafkamon - ported for the new versions as well.

Right now, the setup is missing, please install the dependencies

sudo pip install python-kafka
sudo pip install zkClient

python monitor.py --zserver <localhost> --topology <topology_name> --spoutroot <spout_root>
