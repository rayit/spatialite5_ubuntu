# spatialite5 Ubuntu/Mint

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

### Build
```
make
```
### Install
```
sudo make install 
```

## Spatial tools

### Dependencies
```
sudo apt install libreadosm-dev
```

```
make
```

```
sudo make install
```
