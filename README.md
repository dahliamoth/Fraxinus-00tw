# Fraxinus 00tw
# Fork containing [Mods](https://github.com/dahliamoth/Fraxinus-00tw/tree/main/Mods) that were made by me and used on my personal build

[日本語](README.jp.md) | [ENGLISH](README.md)

Fraxinus 00tw is one of the projects in the Fraxinus community, derived from Fraxinus 00w by Yohei Fukuma (https://x.com/fukumay1).

The designer is SummerOrange (https://x.com/PlasticMikan).

This repository contains the design data for Fraxinus 00tw. Some parts, such as the extruder, bed, control panel, and print head, have selectable options.

![](https://fraxinus.jp/images/community/Fraxinus00tw.png)

## Highlights / Specifications

- A compact CoreXY 3D printer based on Fraxinus 00w.
- Approximate build area is 70 mm in X/Y and about 60 mm in Z.  
  The actual usable range may vary depending on the selected configuration and tuning.
- 3D-printable parts, panel-cut DXF files, assembly manuals, and the BOM are all linked from this repository.
- Selectable configurations are available for the bed, extruder area, feet, control panel, and print head.

## Before You Start

- If you do not already own a 3D printer:  
  This project assumes a certain level of familiarity with 3D printers and their operation. To print the parts for Fraxinus 00tw, assemble them, tune the machine, and maintain it afterward, we strongly recommend owning a 3D printer first.
- If this is your first time building a 3D printer:  
  Building a DIY 3D printer requires broad knowledge across mechanics, electronics, and software. You are welcome to ask on Discord, but please do some basic research first and include enough detail about your setup, the problem, and what you have already tried so others can help effectively. Today it is also possible to use AI to help solve problems, but final judgment and safety checks must still be done by yourself.

## Getting Started

- See [BOM.md](BOM.md) for the bill of materials.
- 3D-printable parts are stored under `3MFs/`.  
  You can download the entire folder [here](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FFraxinus-3D%2FFraxinus-00tw%2Ftree%2Fmain%2F3MFs).  
  See [3MFs/README.md](3MFs/README.md) for how to read file and directory names.
- Panel cut data is stored under `DXFs/`.  
  You can download the entire folder [here](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FFraxinus-3D%2FFraxinus-00tw%2Ftree%2Fmain%2FDXFs).  
  See [DXFs/README.md](DXFs/README.md) for an overview and credits for the panel data.
- Slicer-ready bundled sets are stored under `PrintSets/`.
- Assembly manuals are stored under `Manuals/`.  
  See [Manuals/README.md](Manuals/README.md) for an overview and usage terms.
- See [CHANGELOG.md](CHANGELOG.md) for change history.
- If you are unsure about assembly or part selection, please ask on the Fraxinus Discord.

## Data in This Repository

- `3MFs/Bed` contains bed-related parts.
- `3MFs/Frames` contains frame and panel-related parts.
- `3MFs/PrintHead` contains print-head-related parts.
- `3MFs/Extruder_RearPanel` contains parts around the extruder and rear panel.
- `3MFs/PanelControl` contains control-panel-related parts.
- `3MFs/Electronics_FilamentRouting` contains electronics and filament-routing-related parts.
- `3MFs/XCarriage_ZCarriage_XYGantry` contains carriage and gantry-related parts.
- `PrintSets/Printed Parts for Bambu Studio.3mf` and `PrintSets/Printed Parts for OrcaSlicer - Colorized.3mf` contain bundled print sets.

## Understanding the Configuration

- Fraxinus 00tw is a single base machine configuration.
- However, some parts still have selectable variants depending on preference or use case.
- The main selectable options are as follows.
  - Bed: `normal bed` / `heated bed`
  - Extruder area: `HGX-Lite` / `sherpa mini`
  - Feet: `corn` / `pillar`
  - Control panel: `DPDT SW` / `PWM volume`
  - Print head: `normal` / `IR sensor`
- If you are unsure which combination to use, please ask on Discord.

## License

Multiple licenses apply to this repository.  
This project does not permit unauthorized assembly kit production or sales.  
In particular, documentation, images, the BOM, and instructional materials published under CC BY-NC-SA 4.0 may not be used to create, sell, advertise, or support commercial kits.

### Design Data and Scripts

Design data, scripts, and other design-related data are published under the [GPLv3](LICENSE.md#GPLv3).

### Documentation and Images

Documentation, images, the BOM, and other documentation-related data are published under the [CC BY-NC-SA 4.0](LICENSE.md#CC-BY-NC-SA).

## Contribution

Please contact us on Discord before creating an Issue or Pull Request.  
See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Disclaimer

All use of the data published by this project is at your own risk. The authors and project maintainers provide no warranty and accept no liability for any problems resulting from its use.  
See [LICENSE.md](LICENSE.md) for details.
