# Have you heard of low-code? 

A low-code development platform (LCDP) provides a development environment used to create application software through a graphical user interface. A low-coded platform may produce entirely operational applications, or require additional coding for specific situations.

#### What can you in 4 hours with the Microsoft Power Platform to help front line workers?

A Front Line Workers Accelerator with the Microsoft low-code platform "Microsoft Power Platform"

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


## The Problem

Helping frontline workers complete their day to day tasks is a common business scenario.  The City of Santa Monica publishes their [Building Permit Inspection Schedule as open data](https://data.smgov.net/Permits-Licenses/Permit-Inspections-Schedule/xird-2kxi).  Building inspectors need to travel to various locations throughout the day to inspect building that are under construction.  Building inspector supervisors need to ensure timely delivery of services and analyze overall trends.  Please build something that helps the Building and Safety Division manage their requests for building permit inspections.  

## About The Project

With 4 hours in mind, I divided the time in the following manner:

* Initiate (1h)
  * Reviewing and understading the problem
  * Analysing the dataset
  * Brainstorming a initial solution
  * Creating a mock of how the mobile app should look like
* Implement (2h)
  * Preparing the data
  * Creating the data model
  * Importing the data
  * Creating the low code app
  * Testing
* Prepare (0.5h)
  * Creating deployment script
* Operate (0.5h)
  * Updating the documentation

## Goal

The end goal was a 2 screens mobile app with a galery, a view form and a navigation menu with extra functionality to be developed later on.

*This is the mockup that I've created during the initiate phase:* 
![Product Name Screen Shot][product-screenshot]

## Outcome

A mobile application to be used by inspectors where they are able to visualize a list of active inspections and get more details on a particular inspection.

With more time the following items were to be developed:

<!-- ROADMAP -->
## Roadmap

 - [ ] Finish the navigation component.
 - [ ] Add user context to the data.
 - [ ] Add extra functionality for the navigation menu options.
 - [ ] Extra styling (HTML Controls rather than standard components).
 - [ ] Create a recommendation model to suggest the inspections to be done in the day. 


### Built With

[![powerplatform][powerplatform.js]][powerplatform-url]

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To test the solution you only need to 

* Import the Frontlineworkers Solution.
* Run the Configuration Migration tool.
* Open the Canvas App.

### Prerequisites

* Configuration Migration Tool
[How to Install the Configuration Migration Tool](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/download-tools-nuget#download-tools-using-powershell)

### Installation

1. Download the Frontline Workers solution [https://example.com](https://example.com)
2. Import the Frontline Workers solution into your target environment
   ```sh
   Go to make.powerapps.com and click on 'Solutions'
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>





<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

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

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/hsilvest/Front-Line-Workers-Power-Platform-Solution.svg?style=for-the-badge
[contributors-url]: https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/hsilvest/Front-Line-Workers-Power-Platform-Solution.svg?style=for-the-badge
[forks-url]: https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/network/members
[stars-shield]: https://img.shields.io/github/stars/hsilvest/Front-Line-Workers-Power-Platform-Solution.svg?style=for-the-badge
[stars-url]: https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/stargazers
[issues-shield]: https://img.shields.io/github/issues/hsilvest/Front-Line-Workers-Power-Platform-Solution.svg?style=for-the-badge
[issues-url]: https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/issues
[license-shield]: https://img.shields.io/github/license/hsilvest/Front-Line-Workers-Power-Platform-Solution.svg?style=for-the-badge
[license-url]: https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/hsilvestre
[product-screenshot]: design/images/canvas-app-mockup.png
[powerplatform.js]: https://img.shields.io/badge/Microsoft-Power%20Platform-green
[powerplatform-url]: https://powerplatform.microsoft.com/en-gb/
