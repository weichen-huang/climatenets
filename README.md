<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/weichen-huang/climatenets">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">ClimateNets: Using AI to Fight Climate Change</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/weichen-huang/climatenets"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/weichen-huang/climatenets">View Demo</a>
    ·
    <a href="https://github.com/weichen-huang/climatenets/issues">Report Bug</a>
    ·
    <a href="https://github.com/weichen-huang/climatenets/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

In this project, we focus on short-term extreme precipitation forecasting using deep neural networks, including convolutions and transformers. In particular, we propose a self-attention augmented convolution mechanism for extreme precipitation forecasting, systematically combining attention scores with traditional convolutions to enrich feature data and reduce the expected errors of the results.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Keras](https://keras.io/)
* [TensorFlow](https://www.tensorflow.org/)
* [Pandas](https://pandas.pydata.org)
* [Xarray](https://xarray.pydate.org)
* [Python](https://www.python.org)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Follow the following instructions and install a few software packages. Then Create a conda env and start installation of library dependencies. Download the required datasets from the link below before training models.

### Prerequisites

Install a few software packages before you get started.
* conda env
  ```sh
  conda env update --file ./environment.yml --prune [--debug]
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/weichen-huang/climatenets.git
   ```
2. Install python dependency packages
   ```sh
   conda env update --file ./environment.yml --prune [--debug]
   ```
3. Download the following datasets -
   ```sh
   PRISM - https://ftp.prism.oregonstate.edu/daily/ppt/
   NCEP/NCAR Reanalysis - https://psl.noaa.gov/data/gridded/data.ncep.reanalysis.html
   Global Historical Climatology Network daily (GHCNd) - https://www.ncei.noaa.gov/products/land-based-station/global-historical-climatology-network-daily
   ```
4. Training and evaluating models
   ```sh
   python train.py
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

TODO add more details

_For more examples, please refer to the [Documentation](https://github.com/weichen-huang/climatenets.git)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/weichen-huang/climatenets/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

TODO add more details

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Weichen Huang - [@twitter_handle](https://twitter.com/twitter_handle) - weichen.huang.2022@gmail.com

Project Link: [https://github.com/weichen-huang/climatenets](https://github.com/weichen-huang/climatenets)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

TODO add more details

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/weichen-huang/climatenets.svg?style=for-the-badge
[contributors-url]: https://github.com/weichen-huang/climatenets/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/weichen-huang/climatenets.svg?style=for-the-badge
[forks-url]: https://github.com/weichen-huang/climatenets/network/members
[stars-shield]: https://img.shields.io/github/stars/weichen-huang/climatenets.svg?style=for-the-badge
[stars-url]: https://github.com/weichen-huang/climatenets/stargazers
[issues-shield]: https://img.shields.io/github/issues/weichen-huang/climatenets.svg?style=for-the-badge
[issues-url]: https://github.com/weichen-huang/climatenets/issues
[license-shield]: https://img.shields.io/github/license/weichen-huang/climatenets.svg?style=for-the-badge
[license-url]: https://github.com/weichen-huang/climatenets/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/climatenets.png
