# Museum Meditations Japan

A curated digital guide exploring the intersection of architecture and culture through Japan's most significant museum buildings.

🌐 **Live Site**: [www.museum-meditations-japan.com](https://www.museum-meditations-japan.com)

## Overview

Museum Meditations Japan showcases 37 architecturally significant museums across Japan, featuring works by renowned architects including Tadao Ando, Kengo Kuma, Le Corbusier, Arata Isozaki, and SANAA. The site serves as both a cultural guide and architectural reference, highlighting how museum buildings themselves become part of the art experience.

## Features

- **Interactive Museum Cards**: Browse museums with high-quality images, architectural details, and practical travel information
- **Detailed Modal Views**: Click any museum for expanded information including:
  - Architectural highlights and significance
  - Museum collection descriptions
  - Multiple interior and exterior photographs with attributions
  - Nearby cultural attractions
- **Travel-Optimized Information**: Each listing includes:
  - Nearest train station (critical for Japan travel)
  - City and prefecture location
  - Architectural style and completion year
  - Architect attribution

## Data Structure

The site is powered by a CSV database (`museums_japan.csv`) containing comprehensive information for each museum:

- Museum names (English and Japanese)
- Architect names (English and Japanese)
- Location details (region, prefecture, city, nearest station)
- Architectural information (style, year, highlights, significance)
- Museum experience descriptions
- Image URLs with proper Creative Commons attributions
- Nearby cultural attractions with descriptions and distances

## Technology Stack

- **Frontend**: Pure HTML5, CSS3, and vanilla JavaScript
- **Hosting**: GitHub Pages
- **Data Format**: CSV (comma-separated values)
- **Images**: Hosted on GitHub, primarily from Wikimedia Commons
- **DNS**: Cloudflare
- **Custom Domain**: museum-meditations-japan.com

## Architecture Highlights

The site features museums designed by:

- **Tadao Ando**: Chichu Art Museum, Benesse House Museum, ANDO MUSEUM
- **Kengo Kuma**: Nagasaki Prefectural Art Museum, Nezu Museum, Suntory Museum of Art
- **Le Corbusier**: National Museum of Western Art (UNESCO World Heritage Site)
- **Arata Isozaki**: Kitakyushu Municipal Museum of Art, Oita Art Plaza
- **SANAA (Sejima + Nishizawa)**: 21_21 Design Sight, Teshima Art Museum
- **I.M. Pei**: Miho Museum

## Regional Coverage

Museums span across Japan's major cultural regions:

- **Kanto**: Tokyo metropolitan area museums
- **Kansai**: Kyoto and Osaka region
- **Chugoku**: Including Naoshima art island
- **Kyushu**: Fukuoka, Kumamoto, Nagasaki, and Oita

## Setup and Deployment

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/jamespnz/museum-meditations-japan.git
cd museum-meditations-japan
```

2. Serve the files locally:
```bash
python3 -m http.server 8000
```

3. Open browser to `http://localhost:8000`

### Updating Content

1. Edit `museums_japan.csv` with museum data
2. Ensure proper UTF-8 encoding for Japanese characters
3. Follow existing CSV structure for new entries
4. Commit and push changes to GitHub

### Image Guidelines

- All images sourced from Wikimedia Commons with proper Creative Commons licenses
- Attribution format: "By [Author] - [Source], [License]"
- Images hosted at: `https://raw.githubusercontent.com/jamespnz/museum-meditations-japan/main/images/`
- Recommended image dimensions: 800x600px minimum

## File Structure

```
museum-meditations-japan/
├── index.html              # Main site file
├── museums_japan.csv       # Museum database
├── README.md              # This file
└── images/                # Museum photographs
    ├── museum_name_1.jpg
    ├── museum_name_2.jpg
    └── ...
```

## CSV Data Fields

Each museum entry includes:

- `museum_name` / `museum_japanese`
- `architect` / `architect_japanese`
- `completion_year`
- `architectural_style`
- `region` / `prefecture` / `city`
- `nearest_station` / `nearest_major_city`
- `description`
- `architectural_highlights`
- `significance`
- `accessibility_notes`
- `primary_museum_experience_blurb`
- `nearby_cultural_attraction_name`
- `distance_from_main_attraction`
- `nearby_cultural_attraction_blurb`
- `museum_image_url` / `image_attribution`
- `attraction_1_image_url` / `attraction_1_attribution`
- `attraction_2_image_url` / `attraction_2_attribution`

## Design Principles

1. **Information Hierarchy**: Travel-optimized card layout prioritizes location and access information
2. **Bilingual Support**: Museum names displayed in both English and Japanese
3. **Responsive Design**: Mobile-friendly interface for on-the-go travelers
4. **Visual Focus**: High-quality architectural photography
5. **Accessibility**: Clear typography, semantic HTML, keyboard navigation support

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

This is a personal curatorial project, but suggestions for additional museums or corrections are welcome via GitHub issues.

### Guidelines for Contributions

- Museums must be architecturally significant
- Architect information must be accurate and verifiable
- Images must have proper Creative Commons licensing
- Japanese translations should be verified

## License

- **Code**: MIT License
- **Content**: Curatorial selections and descriptions are original work
- **Images**: Various Creative Commons licenses (see individual attributions)

## Credits

### Site Development
Created by James Park

### Image Sources
All photographs sourced from Wikimedia Commons with proper attribution. Special thanks to the photographers who released their work under Creative Commons licenses.

### Architectural Research
Information compiled from official museum websites, architectural journals, and cultural heritage databases.

## Acknowledgments

This project celebrates the architects who designed these remarkable spaces and the museums that preserve and share cultural heritage. Special recognition to:

- The Japanese architectural tradition of integrating building and environment
- Naoshima's art island project for pioneering museum-as-destination culture
- Japan's commitment to preserving modernist architecture while pushing contemporary boundaries

---

**Last Updated**: October 2025  
**Museums Featured**: 37  
**Regions Covered**: 6  
**Architects Represented**: 25+
