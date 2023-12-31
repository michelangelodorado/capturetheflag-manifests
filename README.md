# capturetheflag-manifests
<a name="readme-top"></a>
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

This project was created from the link below from F5 Labs, author was Shahnawaz Backer:<br>
[https://www.f5.com/labs/learning-center/demystifying-api-attacks-using-gamification](https://www.f5.com/labs/learning-center/demystifying-api-attacks-using-gamification)

<b>Demystifying API Attacks Using Gamification</b><br>
Learn about authentication, authorization, and security misconfiguration in API compromises by exploring this capture-the-flag game.

F5 Labs is introducing a gamified version of a system that lets you hunt for API vulnerabilities on your own to learn how they work. The system simulates some of the errors that are left intentionally or unintentionally in the system and similar issues that have been exploited and resulted in breaches.

<!-- GETTING STARTED -->
## Getting Started

You will set up the practice environment in a Kubernetes cluster (Azure/AWS)

The practice environment consists of two applications:

* <i><b>sbacker/ctfapi:</i></b> The quiz website describing the scenario that needs to be pwned
* <i><b>sbacker/witcherportal:</i></b> The vulnerable portal for challenged


### Prerequisites

* Kubernetes cluster in Azure (AKS) or AWS (EKS)
* Git or have the yaml files uploaded to your K8s master node

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this to quickly deploy the game into your Kubernetes cluster for testing and demo purposes

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Demystifying API Attacks Using Gamification](https://www.f5.com/labs/learning-center/demystifying-api-attacks-using-gamification)
* [ctfd.io](https://ctfd.io/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
