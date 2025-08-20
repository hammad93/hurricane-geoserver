# Start from the GeoServer image
FROM docker.osgeo.org/geoserver:2.28.x

# Your customizations go here
# For example, you might want to set environment variables,
# install additional tools, copy configuration files, etc.

# after troubleshooting apt update

# Example: Setting an environment variable
# ENV MY_CUSTOM_ENV_VAR=my_value
ENV CORS_ENABLED=true
ENV INSTALL_EXTENSIONS=true
ENV STABLE_EXTENSIONS=ysld,ogcapi-features
ENV PROXY_BASE_URL=https://nfc.ai/geoserver
ENV GEOSERVER_CSRF_WHITELIST=nfc.ai
# Example: Copying a custom GeoServer data directory into the container
# COPY my_geoserver_data_dir /geoserver_data_dir
# No CMD or ENTRYPOINT is necessary if you're just using the base image's setup,
# but you can override or specify them if needed.
