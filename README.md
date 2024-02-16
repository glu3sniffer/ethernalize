<!-- Test -->
<a name="readme-top"></a>
<!--
*** Comment
-->



<!-- ETHERNALIZE -->



<br />
<div align="center">
  <a href="https://github.com/glu3sniffer/ethernalize">
    <a name="Ethernalize"></a>
  </a>
  <h3 align="center">Ethernalize</h3>
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

Etheranlize is an upcoming project that allows users to stake their ETH and receive an NFT that can change dynamically funded by the yield generated on Blast. Currently, this project showcases the initial idea with python scripts and will later inclued a front end and actual NFT minting. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

A list of languages/frameworks used so far

* [![Python][Python.com]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

A set of instructions explaining how to run the software:
To get a local copy up and running follow these simple example steps.

### Prerequisites

The following is required to run the scripts
* python3
  ```sh
  sudo apt install python3
  ```

### Installation

1. Locate your wallet public and private keys for the sender and the public key of the receiver
2. Clone the repo
   ```sh
   git clone https://github.com/glu3sniffer/ethernalize.git
   ```
3. Install Python
   ```sh
   npm install
   ```
4. Create a .env file and add your public & private keys and the blast rpc url 
   ```sh
   touch .env
   ```
5. Add the following into the file
   ```sh
   account1="0x..."
   account2="0x..."
   privatekey="..."
   blast_url = "https://sepolia.blast.io"
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Stay tuned.

_For more information, please refer to [Website](https://www.ethernalize.it/#)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Create an on chain inscription of the image file
- [x] Create a viewing system that decodes the image file
- [ ] Create a front end to connect to the viewing system
- [ ] Create the NFT's
- [ ] Focus on cost optimization
    - [ ] Use the native blast yield
    - [ ] Net gas optimizations

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

We welcome contributions. Feel free to suggest new features by doing the following:

1. Fork the repo
2. Create a new branch 
3. Commit your changes 
4. Push to the main branch
5. Open a pull request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Contact (and follow us!) on Twitter - [@Ethernalize](https://twitter.com/your_username)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Read Me Template](https://github.com/othneildrew/Best-README-Template/tree/master)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[Python.com]: https://www.python.org/static/img/python-logo.png
[Python-url]: https://www.python.org
