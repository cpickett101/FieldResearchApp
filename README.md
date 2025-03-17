# Field Research Interactive Map and Slideshow

An interactive web application designed for field researchers, scientists, and outdoor enthusiasts to visualize, organize, and share location-based image collections and research data.

![Flashcard App Screenshot](https://raw.githubusercontent.com/cpickett101/FieldResearchApp/main/FieldResarchApp.png)

## Features

- **Interactive Map**: View your research sites on an OpenStreetMap base map
- **GPS Extraction**: Automatically extracts GPS coordinates from image EXIF data
- **Image Slideshow**: Browse through images from each research location
- **Drag-and-resize Interface**: Adjustable split-screen layout
- **Fullscreen Mode**: Enlarge images for detailed viewing
- **Auto-play Feature**: Automatically cycle through images
- **Marker Clustering**: Efficiently visualize many research sites
- **Google Earth Integration**: Export data as KMZ files to view in Google Earth
- **Mobile Responsive**: Works on tablets and phones as well as desktop computers

## Use Cases

- **Field Research**: Document sample sites, specimens, and environmental conditions
- **Ecological Monitoring**: Track changes in habitats over time
- **Geological Surveys**: Document formations and collect sample data
- **Archaeological Excavations**: Map findings and document artifacts
- **Environmental Education**: Create interactive field trip summaries
- **Travel Documentation**: Organize travel photos by location
- **Real Estate Analysis**: Document properties and neighborhood features

## How It Works

1. **Upload Images**: Select images from your device - the app will extract GPS data if available
2. **View Locations**: Markers appear on the map for each location
3. **Browse Images**: Click markers to view images from that location
4. **Export Data**: Create KMZ files to share or view in Google Earth

## Technical Details

This application is built using modern web technologies:

- **Leaflet.js**: For the interactive mapping functionality
- **Leaflet.MarkerCluster**: For improved visualization of many markers
- **EXIF.js**: For extracting GPS and metadata from images
- **JSZip**: For creating KMZ export files
- **FileSaver.js**: For downloading generated files

All processing happens in the browser - no server required. Your data remains private and is not uploaded to any server.

## Installation

This is a standalone web application with no backend requirements. To run locally:

1. Clone the repository:
```
git clone https://github.com/cpickett/FieldResearchApp.git
```

2. Open `index.html` in a web browser

Alternatively, host the files on any web server or GitHub Pages.

## Offline Usage

This application includes service worker support for offline functionality:

- Images you've already viewed will be available offline
- The map will use cached tiles when available

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [OpenStreetMap](https://www.openstreetmap.org/) for map data
- [Leaflet](https://leafletjs.com/) for the mapping library
- [EXIF.js](https://github.com/exif-js/exif-js) for image metadata extraction
- [JSZip](https://stuk.github.io/jszip/) for KMZ file generation
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) for client-side file saving

---

Created by Christopher Pickett | 2025
