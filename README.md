# Stream Overlays

Some overlays (web pages with a solid colour that is chroma-keyed to become transparent) to use as a graphics layer in OBS Studio.

To run:

    python3 -m http.server

Then access on **http://localhost:8000**

You can add as an Overlay in OBS Studio by adding a _Source_ of type _Browser_, then set the URL to `http://localhost:8000/somedir` depending on the overlay you want to use.
