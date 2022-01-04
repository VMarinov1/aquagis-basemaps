# AquaGIS BaseMaps installation

В настоящото repo са необходимите компоненти за инсталация и конфигурация на AquaGIS MapServer BaseMaps backend

make this folder with respective rights
```commandline
sudo mkdir /mapslabio/
sudo chown -R $USER:$USER
cd /mapslabio/
git clone https://github.com/aqua-gis/aquagis-basemaps
cp -r /mapslabio/aquagis-basemaps/mapserver/ /mapslabio/

```

edit all URI, PORTS, SERVER RESOURCES in the map files

list of map files:

- aquagis_aero_wms.map -> AquaGIS Pernik Aerophoto BaseMap
- aquagis_shumen.map -> AquaGIS Shumen rastermaps 
- aquagis_wms -> AquaGIS DWG based BaseMap

