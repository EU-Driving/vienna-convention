# Vienna Convention - Road Traffic Signs

Complete collection of road traffic signs compliant with the Vienna Convention on Road Signs and Signals. This project contains vector SVG files and a JSON reference catalog for all standardized signs.

## Overview

This repository contains a comprehensive library of road traffic signs based on the Vienna Convention, an international treaty that standardizes road signage across many countries. Each sign is available in vector SVG format, allowing for use at any scale without quality loss.

## Project Structure

```
vienna-convention/
├── road_signs_references.json    # Complete reference catalog
├── Traffic_Signs/                # SVG signs library
│   ├── A:Danger/                 # Danger signs (543 files)
│   ├── B:Priority/               # Priority signs (24 files)
│   ├── C:Prohibitory/            # Prohibitory signs (414 files)
│   ├── D:Mandatory/              # Mandatory signs (102 files)
│   ├── E:Special/                # Special signs (128 files)
│   ├── F:Information/            # Information signs (148 files)
│   ├── G:Direction/              # Direction signs (58 files)
│   └── H:Additional/             # Additional signs (24 files)
└── README.md                     # This file
```

## Sign Categories

### A : Danger
Warning signs indicating potential hazards on the road. Includes dangerous bends, steep gradients, pedestrian crossings, roadworks, and many other situations requiring special attention.

### B : Priority
Signs governing right-of-way at intersections and junctions. Includes priority signs, yield signs, and stop signs.

### C : Prohibitory
Signs indicating prohibitions or restrictions. Includes speed limits, traffic restrictions, and access prohibitions.

### D : Mandatory
Signs indicating obligations for road users. Includes mandatory directions, mandatory lanes, and mandatory equipment.

### E : Special
Signs indicating special situations or facilities. Includes tunnels, level crossings, rest areas, and other road facilities.

### F : Information
Signs providing useful information to users. Includes filling stations, restaurants, hotels, telephones, and other services.

### G : Direction
Direction and orientation signs. Includes signs indicating directions, distances, and destinations.

### H : Additional
Additional and supplementary signs used in combination with other signs to provide additional information.

## File Format

### SVG Files

Signs are provided in SVG (Scalable Vector Graphics) format, which ensures:
- Perfect quality at all scales
- Optimized file size
- Compatibility with all browsers and graphics software
- Easy editing and customization

### Naming Convention

SVG files follow a structured naming convention:

```
VIENNA:[Reference]-[Variant]-[Version][-LHT].svg
```

Examples:
- `VIENNA:A1a-Aa-V1.svg` : Sign A1a, variant Aa, version 1
- `VIENNA:A1a-Aa-V1-LHT.svg` : Left-hand traffic version
- `VIENNA:A12a-Ab-V2.svg` : Sign A12a, variant Ab, version 2

### JSON Reference File

The `road_signs_references.json` file contains a complete catalog with:
- Sign reference (e.g., `VIENNA:A1a`)
- Sign name
- Detailed description
- List of available declinations

Example structure:
```json
{
  "reference": "VIENNA:A1a",
  "name": "Dangerous Bends (left)",
  "description": "Sign A1 may come in two models...",
  "declinations": [
    "VIENNA:A1a-Aa-V1",
    "VIENNA:A1a-Aa-V2",
    ...
  ]
}
```

## Usage

### Viewing Signs

SVG files can be opened directly in:
- Modern web browsers
- Graphics software (Adobe Illustrator, Inkscape, etc.)
- Design tools (Figma, Sketch, etc.)
- Image viewing applications

### Integration in Projects

SVG files can be integrated into:
- Web applications (HTML, CSS)
- Mobile applications
- PDF documents
- Mapping software
- Navigation systems
- Technical documentation

### Finding Signs

To find a specific sign:
1. Consult the `road_signs_references.json` file to identify the reference
2. Navigate to the corresponding folder in `Traffic_Signs/`
3. Select the desired variant and version

## Statistics

- **Total SVG signs** : 1441 files
- **Categories** : 8 main categories
- **Format** : Vector SVG
- **Standards** : Vienna Convention on Road Signs and Signals

## Standards and Compliance

All signs in this collection are based on the Vienna Convention on Road Signs and Signals, an international treaty that establishes common standards for road signage. This convention facilitates understanding of road signage by international drivers and contributes to improving road safety.

## License

Please consult the project's license file for the terms of use of these resources.

## Contributing

Contributions are welcome. If you wish to improve this collection, add new signs, or correct errors, please feel free to submit a pull request.

## Additional Resources

For more information about the Vienna Convention on Road Signs and Signals, consult the official documentation and government resources of your country.

---

*Last updated: 2026*
