<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/iel-amra/Transcendance">
    <img src="https://github.com/iel-amra/Transcendance/blob/main/Transcendance.png?raw=true" alt="Logo" width="400" height="400">
  </a>

  <h3 align="center">Transcendance - The pong</h3>

  <p align="center">
    A fun multiplayer online game !
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

Transcendance is a multiplayer game website, with different features such as
- A multiplayer pong with server-side lag compensation
- A user management system
- A tournament system
- AI oppenents
- 42 API authentification and 2 factors authentification
- Multilanguage support
- 3D graphics
- Statistics about games

The game was developed by a team of five students, each focusing on different features. I personnaly implemented the game's physics, the lag compensation, the AI agent, JWT for authentication, and the input validation for our API.

![Product Name Screen Shot][product-screenshot]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Transcandance was developed and tested only on ubuntu, but should work well on other operating systems since it uses containers.

### Prerequisites

<p>Transceandance requires <code class="language-plaintext highlighter-rouge">docker-compose</code> and <code class="language-plaintext highlighter-rouge">make</code>. 

Installing make on Ubuntu can be done as follows:</p>

```
sudo apt-get update && sudo apt-get install make
```

For docker-compose, here is an install guide : https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository

### Installation

1. Clone the repo
   ```
   git clone git@github.com:iel-amra/Transcendance.git
   ```
2. Create a .env and change it's value if needed :
   ```
   cp .env-example .env
   ```
3. Enter the Transcendance folder and build
   ```
   cd Transcendance && make
   ```

That's it ! So_long is now installed on your machine.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

To start the first map of the game, enter the following command in your terminal :
```
./so_long map/map1.ber
```

You can launch any map you want with the following syntax :
```
./so_long [map_name].ber
```

Keys :
* Deplacement : W,A,S,D or the arrow keys
* Exit the game : Escape
* Activate the fly cheat : V

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Authors
This project was developed by Ihab El Amrani, Erik Avilov, Augustin Cousin, Nicolas Chabli and Julien Alamelle for 42.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Ihab El amrani - [Linkedin](https://www.linkedin.com/in/ihab-el-amrani) - iel-amra@student.42lyon.fr

Project Link: [https://github.com/iel-amra/So_long](https://github.com/iel-amra/So_long)

My github : [https://github.com/iel-amra](https://github.com/iel-amra)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ihab-el-amrani
[product-screenshot]: https://github.com/iel-amra/Transcendance/blob/main/screenshot.png?raw=true