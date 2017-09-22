# Weebly Element Starter App

Simple Node.js application wrapped in a Docker container that helps developers build Weebly Elements

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system,

### Prerequisites

It is expected that you already have a Weebly Developer Account and can login to the [Weebly Developer Admin](https://www.weebly.com/developer-admin/), if you do not you can [Create a Free Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html).

You will need the following software installed to develop the app:

* [Node Version Manager, aka: NVM](https://github.com/creationix/nvm)
* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org)
* [NPM](https://www.npmjs.com/), please note this will install with Node.js except in very limited cases

Accounts you may need/want (if you do not already):

* [Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html)
* [Github](https://github.com)
* [DockerHub](https://hub.docker.com/) will be used in later sample apps
* [NPM](https://www.npmjs.com/signup)

We need API Keys for this app to work, you can obtain those when you [Register a Weebly App](https://dev.weebly.com/register-your-app.html).

Prior to developing any code, please make sure you [read the Weebly App Policy Requrements](https://dev.weebly.com/app-policy-requirements.html) and that your app will not be at risk of being denied during publishing.

#### Clone the Repository

Clone using HTTPS

```
git clone https://github.com/bdeanindy/weebly-element-starter-app.git
```

Remember, you will need API Keys for your Weebly app and a Weebly Developer Site to test this code is working properly, please make sure to [Create a Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html) and to [Register a Weebly App](https://dev.weebly.com/register-your-app.html)

When you are registering your new Weebly App, let's call this app "My Hello World", and set its type to `services`.

### Configurations

Now that you have the code cloned locally, and your new Weebly App API Client ID on-hand, you're ready to get started.

1. Open [manifest.json.tmpl](/manifest.json.tmpl) and replace `{{WEEBLY_CLIENT_ID}}` with the Weebly **Client ID** for the **My Hello World** app you created for the prerequisites.
2. Once you save the changes, rename that file to `manifest.json` and save the changes.
3. Next, commit these changes to history in Git: `git add manifest.json`, then `git commit -m "Update with my app client id"`
4. Next, open the [Weebly Developer Admin](https://www.weebly.com/developer-admin), login if you are not already, and click on the "My Hello World" app if it is not already open

## Deployment

1. Create a **.zip** file of EVERYTHING under the root (this should be the same working directory where the `.git` folder resides).
2. Name or Rename that `.zip` file: `0.1.0.zip` (I've found it helpful to keep my zip file names mapped to the same as my app version)
3. Now you need to **Upload a New Version** of your app's zip file in the Weebly Developer Admin and complete the form for the other required fields
4. Then, click the **Save Draft** link. If any errors are displayed, correct those and click the **Save Draft** link again
5. Next, Go back to the **My Hello World** app's **Versions** tab, and click on the link labeled **Install to Site** and choose your Weebly Developer Site
6. The Editor should immediately open, and you should see the My Hello World element in the editor highlighted in blue
7. Drag the **My Hello World** element on to a page of your Weebly site and play with the settings....TADA, hello world element in Weebly!

## Built With

* [Github](https://github.com)
* [Node.js](https://maven.apache.org/) - JavaScript runtime built on Chrome's V8 JavaScript Engine
* [NPM.js](https://npmjs.org) - Leading package manager for JavaScript

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
