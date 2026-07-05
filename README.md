# Hosting a Full-Stack Application

### **You can use you own project completed in previous courses or use the provided Udagram app for completing this final project.**

---

## Goal

This project aims to take a newly developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers.

# Udagram

### Description

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application. The aws console will start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers. The ```package.json``` scripts will be modified and hard coded secrets will be replaced with environment variables in the code.

After the initial setup, the aws services will be interacted with and manually deploy the application a first time. This will increase knowledge in CI/CD by gradually increasing understanding in all the moving parts in the application through interaction with the CLI.

The CircleCi account will be connected to the Github account to deploy the app. The ```config.yml``` file will make the process reproducible in CircleCi and ensure the process will automatically execute when code is pushed on the main Github branch.



### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```


### Creation Date

> 7/4/2026

### Project Status

> Active


### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

<a href="https://jasmine.github.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jasmine/jasmine-icon.svg" alt="jasmine" width="40" height="40"/> </a>

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework

  <a href="https://angular.io" target="_blank" rel="noreferrer"> <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/> </a>

- [Node](https://nodejs.org) - Javascript Runtime

  <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img width="59" height="49" alt="node_js_logo" src="https://github.com/user-attachments/assets/bc05c6f4-2ccb-41ab-a499-d0cdee52540f" /> </a>

- [Express](https://expressjs.com/) - Javascript API Framework

  <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img width="114" height="40" alt="express_logo" src="https://github.com/user-attachments/assets/922b7eb3-f9a5-45d8-add7-e73f07cff732" /> </a>


## Challenges Faced During Project



## Udacity Mentors Who Have Answered Questions In Knowledge To Help With Project
- 


## Languages

**JavaScript**

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>

**TypeScript**

<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a>


## Tools

**Visual Studio Code** - The application software where the project is edited.

<p align="left"> <img width="43" height="46" alt="VSCode_logo" src="https://github.com/user-attachments/assets/0f8d15c4-276a-46ef-92cd-80a2f1958e76" /> </p>

**AWS** - Services for running the application.

<p align="left"> <img width="49" height="42" alt="aws_logo" src="https://github.com/user-attachments/assets/565f86c2-27d8-491a-8e3b-8d4e976325d0" /> </p>

**CircleCI** - The cloud/based CI/CD platform that automates the application software development process.

<p align="left"> <img width="53" height="53" alt="circleci_logo" src="https://github.com/user-attachments/assets/bc7ea443-5ebe-4413-bc2e-11407ad20609" /> </p>

**GitHub Desktop** - The application software that gives access to the project from _GitHub_ and allows it to be edited in _Visual Studio Code_.

<p align="left"> <img width="46" height="46" alt="GitHub_Desktop_logo" src="https://github.com/user-attachments/assets/bbd2a72d-0953-499e-ab28-e55b11171b83" /> </p>

**ChatGPT** - The application software that answers specific questions of why project has specific problems or why project failed to achieve intended results.

<p align="left"> <img width="49" height="42" alt="ChatGPT_logo" src="https://github.com/user-attachments/assets/34fd410d-3e92-4fc6-8dc7-1be521a8d2a6" /> </p>


## Credits
###### References used while making project

“AWS Logo PNG Transparent & SVG Vector.” _Freebie Supply_, freebiesupply.com/logos/aws-logo/. Accessed 4 July 2026. 

“Circleci Logo PNG Transparent & SVG Vector.” _Freebie Supply_, freebiesupply.com/logos/circleci-logo/. Accessed 4 July 2026.

Dhadhazi. “Nd0067-C4-Deployment-Process-Project-Starter.” _GitHub_, Udacity, 2023, github.com/udacity/nd0067-c4-deployment-process-project-starter. Accessed 4 Jun. 2026.

“GitHub Profile README Generator.” _GitHub Profile Readme Generator | GitHub Profile Readme Generator_, rahuldkjain.github.io/gh-profile-readme-generator/. Accessed 4 Jun. 2026.

“MLA Works Cited: Electronic Sources (Web Publications).” _MLA Works Cited: Electronic Sources - Purdue OWL® - Purdue University_, owl.purdue.edu/owl/research_and_citation/mla_style/mla_formatting_and_style_guide/mla_works_cited_electronic_sources.html. Accessed 4 Jun. 2026.


## License

[License](LICENSE.txt)
