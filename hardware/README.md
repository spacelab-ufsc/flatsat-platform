<h1 align="center">
	SpaceLab FlatSat Platform Hardware
	<br>
</h1>

<h4 align="center">FlatSat platform hardware project (sources, outputs, and documentation).</h4>

<p align="center">
    <a href="">
		<img src="https://img.shields.io/badge/status-development-green?style=for-the-badge">
	</a>
    <a href="">
		<img src="https://img.shields.io/badge/version-0.1-blue?style=for-the-badge">
	</a>
	<a href="">
		<img src="https://img.shields.io/badge/CAD%20tool-altium%20v20.2-9cf?style=for-the-badge">
	</a>
	<a href="">
		<img src="https://img.shields.io/badge/license-CERN-red?style=for-the-badge">
	</a>
	<!---
	<a href="https://github.com/spacelab-ufsc/obdh2/tree/dev/doc/build">
		<img src="https://img.shields.io/badge/for%20more-here-lightgray?style=for-the-badge">
	</a>
	--->
</p>

<p align="center">
  	<a href="#overview">Hardwar overview</a> •
  	<a href="#architecture">Architecture</a> •
  	<a href="#license">License</a> •
  	<a href="#notes">Notes</a>
</p>

<p align="center">
	<img width="45%" src="https://github.com/spacelab-ufsc/flatsat-platform/blob/documentation/doc/figures/flatsat_top_image.PNG">
	<img width="45%" src="https://github.com/spacelab-ufsc/flatsat-platform/blob/documentation/doc/figures/flatsat_bottom_image.PNG">
</p>

## Hardware overview

Currently in v0.1, the SpaceLab FlatSat Platform is a 300mmx220mm PCB composed by the following main hardware components:

* 7 PC104 connectors, one of them with inverted pinout.
* RBF pin header for a jumper and Kill-Switches with SPDTs.
* External charging for batteries thought JST and picoblade connectors.
* 2 separate binding posts (2 sets) for controled power supply and pin headers for external wiring. 
* 4 UART channels to micro USB B using FT4232H IC converter.
* 4 SMA connectors for antennas interfacing.

## Hardware architecture diagram

<!---
<p align="center">
	<img width="70%" src="https://github.com/spacelab-ufsc/obdh2/blob/master/doc/figures/block_diagram.pdf">
</p>
--->

TBD

<!---

## Version

TBD

--->

## License

The hardware part of this project is licensed under CERN Open Hardware License, version 2.

## Notes

More info about the SpaceLab: [GitHub](https://github.com/spacelab-ufsc/spacelab) and [Website](https://spacelab.ufsc.br/en/home/).