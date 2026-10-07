# nyc-saved
my saved spots of the best city in the world

Serve this repository root with a local web server (for example,
`python3 -m http.server 8000`), then open `http://localhost:8000/`.
The map loads its styles and `data/nyc-recommendations.geojson` relative to
`index.html`, so the same layout works under a hosted repository subpath.

`prepare-data.ipynb` uses paths relative to the repository root. Run it with
that working directory. Its eight input CSVs belong in `data/raw/`; they
were not present in the original project and are not included here. The
notebook generates intermediate CSVs in `data/` before exporting the map's
GeoJSON. The included GeoJSON is sufficient to run the map without rerunning
the notebook.
