# Weebly Element Starter App

Simple Node.js application wrapped in a Docker container that helps developers build Weebly Elements

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system,

### Prerequisites

It is expected that you already have a Weebly Developer Account and can login to the [Weebly Developer Admin](https://www.weebly.com/developer-admin/), if you do not you can [Create a Free Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html).

You will need the following software installed to run the app using Docker:

* [Docker](https://www.docker.com/)

Optional software required if not using Docker:

* [Node Version Manager, aka: NVM](https://github.com/creationix/nvm)
* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org)
* [NPM](https://www.npmjs.com/), please note this will install with Node.js except in very limited cases

Accounts you may need/want (if you do not already):

* [Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html)
* [Github](https://github.com)
* [DockerHub](https://hub.docker.com/)
* [NPM](https://www.npmjs.com/signup)

We need API Keys for this app to work, you can obtain those when you [Register a Weebly App](https://dev.weebly.com/register-your-app.html).

Prior to developing any code, please make sure you [read the Weebly App Policy Requrements[(https://dev.weebly.com/app-policy-requirements.html) and that your app will not be at risk of being denied during publishing.

#### Docker Installation Verification

Before we begin, make sure you have [installed Docker](https://docs.docker.com/engine/installation/).
You can test that docker is properly installed by running the following from a terminal

```
docker run hello-world
```

Then, make sure you are running at least Docker version 1.3 or higher

```
docker --version
```

Remember, you will need API Keys for your Weebly app and a Weebly Developer Site to test this code is working properly, please make sure to [Create a Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html) and to [Register a Weebly App](https://dev.weebly.com/register-your-app.html)

### Installing

Using Docker

```
Give the example
```

Using Git (you can do this using HTTPS or SSH, just replace `<THIS_REPOSITORY_CLONE_URI>` with your preferred format

```
git clone <THIS_REPOSITORY_CLONE_URI>
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

To execute the automated tests in this source code. You can read the full set of test commands used in the [package.json](/package.json) file in the `scripts` property.

```
npm test
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Docker](https://www.docker.com/) - The world's leading software container platform
* [Node.js](https://maven.apache.org/) - JavaScript runtime built on Chrome's V8 JavaScript Engine
* [NPM.js](https://npmjs.org) - Leading package manager for JavaScript
* [Express.js](https://rometools.github.io/rome/) - Fast, unopinionated, minimalist web framework for Node.js

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on the Weebly Code of Conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)
* **Benjamin Dean** - *Core Contributor* - [bdeanindy](https://github.com/bdeanindy)

## Contributors

* Submit a PR that is merged to see your name here!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Weebly Engineering Team for all their efforts
* Robin Whitmore - the initial author of the Weebly Developer Docs which made this possible
* You, and all the Weebly App Developers who make Weebly awesome with your awesome questions and challenging issues

