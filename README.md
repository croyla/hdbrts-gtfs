# hdbrts-gtfs
This repo houses GTFS feeds built from the [HDBRTS website](https://hdbrts.com).
### gtfs.zip
This file stores data in the original format. If the HDBRTS website had two routes with the same name, destinations, and stop sequences they will be separate routes here. Good for research purposes and data processing.
### gtfs_compat.zip
This file stores data in the most compatible format. Routes are merged for simplicity, route names are Title Case, trips may have different stop sequences and directions. Ideal for Passenger Information Services like [transitrouter](https://transitrouter.pages.dev/#/hublidharwad/), [catenary maps](https://maps.catenarymaps.org), etc.

