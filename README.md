[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Twitter][Twitter-shield]][Twitter-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/MikeS11/MiSTerCRT">
    <img src="Images/MiSTerCRT2.jpg?raw=true" alt="" width="534" height="394">
  </a>
  <a href="https://github.com/MikeS11/MiSTerCRT">
    <img src="Images/MiSTerCRT3.jpg?raw=true" alt="" width="382" height="240">
  </a>
  <h3 align="center">MiSTerCRT - S-Video / Composite Adapter</h3>

  <p align="center">
  

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#Build-Requirements)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## About The Project
Wanted to add a open source option for getting S-Video / Composite out of a MiSTer and add some flexiblity to tune the NTSC crystal through a trim capacitor.

### Getting Started
You can use either power from the 5V VGA port (Through the IO Board dip switch) or directly through USB. Make sure you only use one of those options.

Also I've added a trim capacitor to tune the NTSC crystal if required. (I've noticed some cores tend to have some additional flicker that can be tuned to improve the image through a trim capacitor.

### Build Requirements:
  
|QUANTITY |	PART NUMBER	|	DESCRIPTION	| UNIT PRICE (Canadian)	|
|  ------------- | ------------- | ------------- | ------------- |
| 1		 |     CP-2240-ND		|	CONN RCPT FMALE MINI DIN 4P SLDR	|  2.38000		|
| 1		 |     CP-1421-ND		|	CONN RCA JACK MONO 3.2MM R/A		  |  2.16000		|
| 1		 |     XC584CT-ND		|	CRYSTAL 3.579545MHZ 17PF SMD		  |  2.47000		|
| 1		 |     AD724JRZ-ND		|	IC ENCODER RGB TO NTSC 16-SOIC		|  26.77000	|
|1	|	609-10033526-N3222MLFCT-ND	|MINI USB B TYPE RECEPT	|		1.09000		|
|1	|	1727-3776-ND	|		IC INVERTER 6CH 6-INP 14SO	|	0.51400	|
|1 | 	311-1.00KCRCT-ND| 		RES SMD 1K OHM 1% 1/8W 0805 | 0.02340			| 
| 6	|	RMCF0805FT75R0CT-ND		|RES 75 OHM 1% 1/8W 0805		|	0.01540		|  
|2 | 311-10.0KCRCT-ND| 	RES SMD 10K OHM 1% 1/8W 0805 | 0.02340	|
|1	|	13-RC2512FK-071MLCT-ND	|	RES SMD 1M OHM 1% 1W 2512	|	0.47300		|
|5 | 399-1171-1-ND	| CAP CER 0.1UF 50V X7R 0805 | 0.11020	|
|2 | 399-15693-1-ND| 		CAP CER 10UF 10V X7R 0805 | 0.85900		|  
|1	|	311-4241-1-ND		|	CAP CER 62PF 50V NPO 0805		|0.14200		|
|1	|	720-VJ0805A470GXJPW1BCCT-ND	|CAP CER 47PF 16V C0G/NP0 0805	|	0.22600		|   
|3	|	399-9744-1-ND		|	CAP TANT 220UF 20% 10V 2917	|	1.90000		|  
| 1		 |     SG9212-ND		|	  CAP TRIMMER 5-25PF 25V SMD		   |   1.40000	|
| 1		 |   XM4L-1542-132  | CONN D-SUB HD RCPT 15P R/A SLDR  | 4.47000 | 

If you need jumpers, S9001-ND, CONN JUMPER SHORTING GOLD FLASH

### Prerequisites


<p align="center">
<img src="Images/MisterCRT.jpg?raw=true" alt=""></p>
<p align="center">
<img src="Images/MisterCRT3.jpg?raw=true" alt=""></p>
<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Mike Simone - [@mikesimone3](https://twitter.com/mikesimone3) 

Project Link: [https://github.com/MikeS11/MiSTerCRT](https://github.com/MikeS11/MiSTerCRT)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/MikeS11/MiSTerCRT.svg?style=flat-square
[contributors-url]: https://github.com/MikeS11/MiSTerCRT/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MikeS11/MiSTerCRT.svg?style=flat-square
[forks-url]: https://github.com/MikeS11/MiSTerCRT/network/members
[stars-shield]: https://img.shields.io/github/stars/MikeS11/MiSTerCRT.svg?style=flat-square
[stars-url]: https://github.com/MikeS11/MiSTerCRT/stargazers
[issues-shield]: https://img.shields.io/github/issues/MikeS11/MiSTerCRT.svg?style=flat-square
[issues-url]: https://github.com/MikeS11/MiSTerCRT/issues
[license-shield]: https://img.shields.io/github/license/MikeS11/MiSTerCRT.svg?style=flat-square
[license-url]: https://github.com/MikeS11/MiSTerCRT/blob/master/LICENSE.txt
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=flat-square&logo=Twitter&colorB=555
[twitter-url]: https://Twitter.com/mikesimone3
[product-screenshot]: images/screenshot.png

