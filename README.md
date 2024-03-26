# hurricane-geoserver
A repository that hosts code for GeoServer related to deep learning forecasts of tropical storms.

## Container
`sudo docker run -it -p8080:8080 --mount type=bind,src=/home/hammad/geoserver,target=/opt/geoserver_data --env INSTALL_EXTENSIONS=true --env STABLE_EXTENSIONS="netcdf" docker.osgeo.org/geoserver:2.25.x`
