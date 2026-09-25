# imagestamper

Open `index.html` in a browser (or host it with GitHub Pages). Add a photo and the page puts a grey bar across the top with the capture date/time and GPS coordinates it reads from the photo's EXIF metadata. You can edit the text, bar colour, opacity and height, add a second line (for example an address looked up from the coordinates), and then download the stamped image.

Everything runs in the browser, so photos are never uploaded. The one exception is the optional address lookup, which sends the coordinates to OpenStreetMap Nominatim.
