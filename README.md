# spatialite5 Ubuntu/Mint

If you continue, an additional ssh daemon will be started at port 
'1022'. 

(
If older version installed
```
sudo apt remove spatialite-tools
sudo apt remove libspatialite7
```
)

## Compile

### Dependencies
```
sudo apt install libfreexl-dev libproj-dev libsqlite3-dev  libgeos-dev  librttopo-dev  libxml2-dev libminizip-dev
```

```
wget http://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz
```
```
tar xvfz libspatialite-5.0.1.tar.gz
```
```
cd libspatialite-5.0.1
./configure
```

### Build
```
make
```
### Install
```
sudo make install 
```

## Spatial tools

```
wget http://www.gaia-gis.it/gaia-sins/spatialite-tools-sources/spatialite-tools-5.0.1.tar.gz
```

### Dependencies
```
sudo apt install libreadosm-dev
```

```
make
```

```
sudo make install
sudo apt-get install libsqlite3-mod-spatialite

```
