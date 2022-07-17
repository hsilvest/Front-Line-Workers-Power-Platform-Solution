# Have you heard of low-code? 

A low-code development platform (LCDP) provides a development environment used to create application software through a graphical user interface. A low-coded platform may produce entirely operational applications, or require additional coding for specific situations.

#### What can you do in 4 hours leveraging Microsoft Power Platform to help front line workers?

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


<!-- GETTING STARTED -->
## Getting Started

To test the solution you only need to 

* Import the [FrontLineWorkers_1_0_0_0_managed.zip](https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/blob/main/FrontLineWorkers_1_0_0_0_managed.zip).
* Run the Configuration Migration tool.

### Prerequisites

* Configuration Migration Tool
[How to Install the Configuration Migration Tool](https://docs.microsoft.com/en-us/power-apps/developer/data-platform/download-tools-nuget#download-tools-using-powershell)

### Installation

1. Download the Frontline Workers solution [FrontLineWorkers_1_0_0_0_managed.zip](https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution/blob/main/FrontLineWorkers_1_0_0_0_managed.zip)
2. Import the Frontline Workers solution into your target environment
   ```sh
   1. Go to make.powerapps.com and click on 'Solutions'
   2. Click on "Import Solution"
   3. Select the "FrontLineWorkers_1_0_0_0_managed.zip"
   4. ..
   5. Import configuration data
        Start the Configuration Migration tool. Double-click DataMigrationUtility.exe in the folder: [your folder]\Tools\ConfigurationMigration\

        On the main screen, click Import data, and click Continue.

        On the Login screen, provide authentication details to connect to your environment from where you want to import data. If you have multiple organizations on the Dynamics 365 server, and want to select the organization where to import the configuration data, select the Always display list of available orgs check box. Click Login.

        If you have multiple organizations, and you selected the Always display list of available orgs check box, the next screen lets you choose the organization that you want to connect to. Select an organization to connect to.

        Provide the data file. (.zip) to be imported. Browse to the data file, and select it. Click Import Data.

        This step is applicable only if the data that you are importing contains the user information of the source system. Enter mapping user information on the target system. You can either map all of them to the user who is running the import process or map to individual users by using a user map file (.xml). If you choose the latter, you will have to either specify an existing user map file or the tool can generate it for you. If you generate a new file, fill in the mapping user name in the New parameter for every user on the source server. Select the user map file in the tool when you are done, and click OK.
   ```
3. Run the configuration migration NPM packages
   ```sh
   npm install
   ```
4. Open the Canvas App your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

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


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact

Henrique Souza - [@your_twitter](https://twitter.com/hsilvest) - hs.ccti@gmail.com

Project Link: [https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution](https://github.com/hsilvest/Front-Line-Workers-Power-Platform-Solution)


<!-- MARKDOWN LINKS & IMAGES -->
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
