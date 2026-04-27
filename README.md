# ESP Mini Drone

Compact mini drone CAD project prepared for open-source sharing.

## Overview
This repository contains the core CAD files for a mini drone design, including Fusion 360 source and printable STL exports.

## Repository Structure

```text
ESP_mini_Drone/
|-- cad/
|   |-- fusion360/
|   |   `-- New_Drone.f3z
|   `-- stl/
|       |-- New_Drone_BODY.stl
|       `-- New_Drone_TOP.stl
|-- docs/
|   `-- BUILD_GUIDE.md
|-- media/
|   `-- screenshots/
|       |-- Screenshot 2026-04-27 092942.png
|       |-- Screenshot 2026-04-27 093122.png
|       `-- Screenshot 2026-04-27 093219.png
|-- .gitignore
|-- LICENSE
`-- README.md
```

## Files Included
- `cad/fusion360/New_Drone.f3z`: Editable Fusion 360 archive.
- `cad/stl/New_Drone_BODY.stl`: Main body printable mesh.
- `cad/stl/New_Drone_TOP.stl`: Top cover printable mesh.

## Preview

![Drone Screenshot 1](media/screenshots/Screenshot%202026-04-27%20092942.png)
![Drone Screenshot 2](media/screenshots/Screenshot%202026-04-27%20093122.png)
![Drone Screenshot 3](media/screenshots/Screenshot%202026-04-27%20093219.png)

## Recommended Workflow
1. Open the `.f3z` file in Fusion 360 for design edits.
2. Export updated STL files to `cad/stl/` for printing.
3. Update screenshots in `media/screenshots/` after major design revisions.
4. Document changes in pull requests before merging.

## How To Contribute
1. Fork the repository.
2. Create a feature branch.
3. Commit with clear messages.
4. Open a pull request with screenshots and change details.

## License
This project is licensed under the MIT License. See `LICENSE` for details.
