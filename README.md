<!--
*** Using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT SHIELDS -->
[![Workflow][workflow-shield]][workflow-url]
[![Issues][issues-shield]][issues-url]
[![Version][version-shield]][version-url]
[![Stargazers][stars-shield]][stars-url]
[![Forks][forks-shield]][forks-url]
[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br>
<div align="center">
  <a href="https://github.com/tberey">
    <img src="public/assets/logo.png" alt="TomCo (Technology & Online Media Company) Logo" width="200" height="100">
  </a><br><br>
  <div align="center"><h1>TS-Node-Electron-AWS-S3-App</h1>A robust Electron application, that serves a REST API to interact with AWS S3.</div>
  <div align="right">
    <br>
    <a href="https://github.com/tberey/ts-node-electron-aws-s3-app/blob/development/README.md"><strong>Documentation »</strong></a>
    <br>
    <a href="#usage">View Demo</a>
    ·
    <a href="https://github.com/tberey/ts-node-electron-aws-s3-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/tberey/ts-node-electron-aws-s3-app/issues">Request Feature</a>
  </div>
</div>



<!-- TABLE OF CONTENTS -->
<details open="open" style="padding:4px;display:inline;border-width:1px;border-style:solid;">
  <summary><b style="display: inline-block"><u>Contents</u></b></summary>
    <ol>
        <li>
        <a href="#about-this-project">About</a>
        <ul>
            <li><a href="#tech-stack">Tech Stack</a></li>
        </ul>
        </li>
        <li>
        <a href="#startup">Startup</a>
        <ul>
            <li><a href="#prerequisites">Prerequisites</a></li>
            <li><a href="#installation">Installation</a></li>
        </ul>
        </li>
        <li>
        <a href="#usage">Usage</a>
        <ul>
            <li><a href="#screenshots">Screenshots</a></li>
        </ul>
        </li>
        <li><a href="#roadmap">Roadmap</a></li>
        <li><a href="#changelog">Changelog</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#acknowledgements">Acknowledgements</a></li>
    </ol>
</details><hr><br>



<!-- ABOUT THis PROJECT -->
## About This Project
This is a Electron application, built in Node and TypeScript, that delivers a client a REST API to fully interact with AWS's S3 buckets. This is not a web application directly, but it is a web-app packaged into an Electron window, that runs like an executable, using Chromium browser tech.

### Tech Stack
* [Typescript](https://www.typescriptlang.org/)
* [NodeJS](https://nodejs.org/en/)
* [Electron](https://www.electronjs.org/)
* [ExpressJS](https://expressjs.com/)
* [AWS](https://aws.amazon.com/)
* [EJS](https://ejs.co/)
* [Axios](https://axios-http.com/)
* [fs](https://nodejs.org/api/fs.html)
* [Rollbar](https://rollbar.com/)
* [ESLint](https://eslint.org/)
* [MochaChai](https://mochajs.org/)

<br><hr><br>



<!-- STARTUP -->
## Startup
For help or guidance in downloading and running the application, see the following subsections.
<br>

#### Prerequisites
[You must have npm (node package manager) and Nodejs installed on your system!](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

1. Setup npm:
  ```sh
  npm install npm@latest -g
  ```
<br>

#### Installation
1. Clone/Download:
  ```sh
  git clone https://github.com/tberey/ts-node-electron-aws-s3-app.git
  ```
2. Install:
  ```sh
  npm install && npm update
  ```
3. Start:
  ```sh
  npm run start:app
  ```

<br><hr><br>



<!-- USAGE EXAMPLES -->
## Usage
This is a electron application, which means it runs on your system, rather than a browser web app (yes, electron is technically just doing what a web browser does).<br>As Such, simply install and run this application and the window will load automatically as if running an executable.

| Endpoint | Action/Desc. | Full URI <i>(hosted locally, for some port; e.g.: 3000)</i> |
|:---|:---|:---|
| <ul><li>"/"</li></ul> | Status: 200 | <ul><li>"http://localhost:3000/"</li></ul> |

<br>

### Screenshots

Logginf Sample:

![Screenshot#1](https://github.com/tberey/tomco-hq/blob/development/screenshots/local-logs-sample.png?raw=true)

<br><hr><br>



<!-- ROADMAP -->
## Roadmap
Below is the refined and confirmed roadmap, that has been planned for completion. See [open issues][issues-url] and also the [project board][project-url], for any other proposed features or known issues, which may not be listed below.

| Feature/Task/Bugfix | Details | Version <i>(if released)</i> | Notes |
|:---|:---|:---|:---|
| <i>Bug#1</i> | <i>Bug details...</i> | <i>0.0.1</i> | <i>example#1</i> |
| <i>Feature#4</i> | <i>Feature details...</i> |   | <i>example#2</i> |

<br><hr><br>



<!-- CHANGELOG -->
## Changelog

| Version | Date | Changes |
|:---|:---|:---|
| 1.0.0 | 2021-07-10 | <ul><li>Initial Commit.</li><li>Add inital directory structure and files.</li><li>Add Screenshots directory, and images.</li><li>Create and format README.md</li></ul> |

<br><hr><br>



<!-- CONTRIBUTING -->
## Contributing
Contributions are welcomed and, of course, **greatly appreciated**.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/Feature`)
3. Commit your Changes (`git commit -m 'Add some Feature'`)
4. Push to the Branch (`git push origin feature/Feature`)
5. Open a Pull Request.

<br><hr><br>



<!-- CONTACT -->
### Contact

<b>Tom Berey</b>; <i>Project Manager, Lead Developer, Principal Tester & Customer Services</i>;<br>tomberey1@gmail.com;

* [Issues & Requests][issues-url]
* [My Other Projects](https://github.com/tberey?tab=repositories)
* [Personal Website](https://tberey.github.io/)
* [Linked In](https://uk.linkedin.com/in/thomas-berey-2a1860129)

<br>

<!-- ACKNOWLEDGEMENTS -->
### Acknowledgements

* [Me](https://github.com/tberey)



<br><br><hr><div align="center">TomCo&trade; (Technology & Online Media Company &copy;)</div>




<!-- SPECIFIC URLS - NEED CHANGING PER PROJECT -->
[workflow-shield]: https://github.com/tberey/ts-node-electron-aws-s3-app/actions/workflows/codeql-analysis.yml/badge.svg
[workflow-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/actions
[version-shield]: https://img.shields.io/github/v/release/tberey/ts-node-electron-aws-s3-app
[version-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/releases/
[stars-shield]: https://img.shields.io/github/stars/tberey/ts-node-electron-aws-s3-app.svg
[stars-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/stargazers
[contributors-shield]: https://img.shields.io/github/contributors/tberey/ts-node-electron-aws-s3-app.svg
[contributors-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/tberey/ts-node-electron-aws-s3-app.svg
[forks-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/network/members
[issues-shield]: https://img.shields.io/github/issues/tberey/ts-node-electron-aws-s3-app.svg
[issues-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?logo=linkedin&colorB=555
[linkedin-url]: https://uk.linkedin.com/in/thomas-berey-2a1860129
[project-url]: https://github.com/tberey/ts-node-electron-aws-s3-app/projects