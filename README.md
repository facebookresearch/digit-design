# DIGIT-DESIGN

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](LICENSE)
<a href="https://digit.ml/">
<img height="20" src="/docs/digit-logo.svg" alt="DIGIT-logo" />
</a>

<img height="300" src="/docs/digit-render.png" alt="DIGIT-render" class="center"/>

Manufacturing design files for the [DIGIT tactile sensor](https://digit.ml).

**For updates and discussions please join the #DIGIT channel at the [www.touch-sensing.org](https://www.touch-sensing.org/) community.**

## Content

This repository contains the documentation and manufacturing files for the plastics enclosure, elastomer, electronics and the firmware binary.

## Design Notes

Due to some parts being out of stock due to shortages, we recommend the following part substituions:

* Digit Main PCB, Camera, OVM7692-RAAA with OVM7692-RYAA
* Digit Main PCB, MCU, FT900-R with FT900Q-C-T
* Digit Flex PCB, LEDs, ARGB1313HS-TR with 19-337C/RSBHGHC-A88/4T
    * Note: this change is only compatible with Digit Flex rev. 2021-2

## Quick Start

Manufacturing and assembly documentation is found in the [Quick Start Guide](DIGIT_Quick_Start_Guide.pdf)

The manufacturing files are released in [releases](releases) for PCBA fabrication.

## Questions and Contributing

If you have questions or need help with the content of this repo please open a ticket.
We welcome useful contributions to the repo -- if you want to contribure please read [how to contribute](CONTRIBUTING.md).

## License
These design files are licensed under CC-by-NC, as found in the [LICENSE](LICENSE) file.

## Citing
If you use this project in your research, please cite this [paper](https://arxiv.org/abs/2005.14679):

```BibTeX
@Article{Lambeta2020DIGIT,
  author  = {Lambeta, Mike and Chou, Po-Wei and Tian, Stephen and Yang, Brian and Maloon, Benjamin and Victoria Rose Most and Stroud, Dave and Santos, Raymond and Byagowi, Ahmad and Kammerer, Gregg and Jayaraman, Dinesh and Calandra, Roberto},
  title   = {{DIGIT}: A Novel Design for a Low-Cost Compact High-Resolution Tactile Sensor with Application to In-Hand Manipulation},
  journal = {IEEE Robotics and Automation Letters (RA-L)},
  year    = {2020},
  volume  = {5},
  number  = {3},
  pages   = {3838--3845},
  doi     = {10.1109/LRA.2020.2977257},
}
```
