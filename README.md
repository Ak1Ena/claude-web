# PhotoTrace — Where Was This Taken?

PhotoTrace is a lightweight, elegant web application that extracts embedded GPS coordinates from your photos and pinpoints the exact location on a live interactive map.

## ✦ Features

- **EXIF Extraction:** Automatically reads EXIF metadata from JPEG, TIFF, and HEIC/HEIF images.
- **Interactive Mapping:** Displays the photo's location using Leaflet and OpenStreetMap.
- **Metadata Viewer:** Shows detailed camera settings, including:
  - Camera Make & Model
  - Date & Time Original
  - Resolution
  - Aperture (f-stop)
  - Shutter Speed
  - ISO & Focal Length
  - GPS Altitude & Coordinates
- **Direct Links:** Quick access to view the location in Google Maps or Street View.
- **HEIC Support:** Handles modern mobile photo formats with on-the-fly conversion for previews.
- **Privacy Focused:** All processing happens locally in your browser. Your photos are never uploaded to a server.

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Libraries:**
  - [Leaflet](https://leafletjs.com/) - Interactive maps
  - [exif-js](https://github.com/exif-js/exif-js) - Metadata extraction (via CDN)
  - [heic2any](https://alexcorvi.github.io/heic2any/) - HEIC to JPEG conversion (via CDN)
- **Typography:** Google Fonts (Playfair Display, DM Sans, JetBrains Mono)

## 🚀 Getting Started

Since this is a client-side web application, you can run it directly by opening `index.html` in any modern web browser.

1. Clone or download this repository.
2. Locate `index.html` in your file explorer.
3. Open it with your preferred browser (Chrome, Firefox, Safari, Edge).

## 💡 How It Works

1. **Drop a Photo:** Drag and drop an image into the dashed area or click to select one.
2. **Metadata Analysis:** The application scans the binary data of the file to find the EXIF header.
3. **Location Pinpointing:** If GPS coordinates are found, they are converted to decimal degrees and plotted on the map.
4. **Explore:** Use the map to see exactly where the photo was captured, or jump to Google Maps for more detail.

---
*Created with a focus on simplicity and aesthetic utility.*
