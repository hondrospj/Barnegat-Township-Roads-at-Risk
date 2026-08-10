# Barnegat Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Barnegat Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01409125, Barnegat Light
- PETSS / NOAA station: 8533615
- NAVD88 thresholds: 2.32 ft minor, 3.32 ft moderate, 4.32 ft major
- MLLW thresholds: 3.5 ft minor, 4.5 ft moderate, 5.5 ft major
- MLLW = NAVD88 + 1.18 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Barnegat Township boundary at 19.7-foot adaptive resolution.
