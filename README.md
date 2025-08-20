# hurricane-geoserver
A repository that hosts code for GeoServer related to deep learning forecasts of tropical storms.

# Container
The container runs the application on port 6004. Navigate to localhost:6004/geoserver for demo. Set the Geoserver admin pass like `-e GEOSERVER_ADMIN_PASSWORD=invalidpass123`.

```bash
cd docker/
docker build -t geosever .
docker run -d -p 6004:8080 -e GEOSERVER_ADMIN_PASSWORD geoserver
```

## References
https://github.com/geoserver/docker?tab=readme-ov-file#environment-variables