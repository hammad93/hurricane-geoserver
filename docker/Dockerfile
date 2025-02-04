# Start from the GeoServer image
FROM docker.osgeo.org/geoserver:2.26.2

# Your customizations go here
# For example, you might want to set environment variables,
# install additional tools, copy configuration files, etc.

# after troubleshooting apt update
RUN chmod 1777 /temp
# install python
RUN apt install python3 python3-venv
RUN python3 -m venv venv .
RUN source ./venv/bin/activate

# Example: Setting an environment variable
# ENV MY_CUSTOM_ENV_VAR=my_value

# Example: Copying a custom GeoServer data directory into the container
# COPY my_geoserver_data_dir /geoserver_data_dir

# No CMD or ENTRYPOINT is necessary if you're just using the base image's setup,
# but you can override or specify them if needed.
