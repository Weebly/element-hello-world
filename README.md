# Weebly Element Hello World 

Simple Node.js application to help developers understand how Weebly Elements are constructed.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

It is expected that you already have a Weebly Developer Account and can login to the [Weebly Developer Admin](https://www.weebly.com/developer-admin/), if you do not you can [Create a Free Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html).

You will need to define a new Weebly App named `Hello World` to [Register a Weebly App](https://dev.weebly.com/register-your-app.html).

**NOTE:** Prior to developing any custom code, please make sure you [read the Weebly App Policy Requrements](https://dev.weebly.com/app-policy-requirements.html) and that your app will not be at risk of being denied during publishing.

### Get the Code

There are two ways you can get the code onto your local workstation.

#### Clone with Git

Clone using Git

```
git clone https://github.com/weebly/weebly-element-hello-world.git
```

#### Download the `.zip`

1. Download the `.zip` file here: [https://github.com/weebly/weebly-element-hello-world/archive/master.zip](https://github.com/weebly/weebly-element-hello-world/archive/master.zip).
2. Extract the `weebly-element-hello-world.zip` file contents:
    * [How to extract Zip files on Windows](https://support.microsoft.com/en-us/help/14200/windows-compress-uncompress-zip-files)
    * [How to extract Zip files on Mac](https://support.apple.com/kb/PH25411?locale=en_US)
    * [How to extract Zip files on Ubuntu](https://askubuntu.com/questions/86849/how-to-unzip-a-zip-file-from-the-terminal)
    * From Linux command line: `tar -xvf weebly-element-hello-world.zip -C /destination/directory/`

### Get your Weebly App API Keys

**OPTIONAL** This step is only required if you plan on integrating your element with the [Weebly REST API](https://dev.weebly.com/about-rest-apis.html).

Make sure to [Create a Weebly Developer Account](https://dev.weebly.com/create-a-developer-account.html), if you have not already.

You will need your **Weebly App's API Keys** and a **Weebly Developer Site** in order for this code to work properly after it is deployed.

Next, please [Register a Weebly App](https://dev.weebly.com/register-your-app.html) to obtain your API Keys.

While registering your new Weebly App, give it the name "Hello World", and set the type to `services`.

### Configurations

Now that you have the code on your workstation, and your new Weebly App API Keys on-hand, you will need to update the code prior to deployment to Weebly.

1. Open [manifest.json.tmpl](/manifest.json.tmpl) and replace `{{WEEBLY_CLIENT_ID}}` with the Weebly **Client ID** for the **Hello World** app you created for the prerequisites.
2. Once you save the changes, rename that file to `manifest.json` and save the changes.
3. Next, open the [Weebly Developer Admin](https://www.weebly.com/developer-admin), login if you are not already, and click on the "Hello World" app if it is not already open

## Deployment

1. Create a **.zip** file of EVERYTHING within the root directory
2. Name or Rename the newly created `.zip` file: `0.1.0.zip` (I've found it helpful to keep my zip file names mapped to the same as my app version value in the `manifest.json` file)
3. Login to the [Weebly Developer Admin Portal](https://www.weebly.com/developer-admin/)
4. Choose your app from the list, if you haven't already.
5. Click **Upload a New Version** of your app's zip file in the Weebly Developer Admin and complete the form for the other required fields
6. Then, click the **Save Draft** link. __If any errors are displayed, correct those and try clicking the **Save Draft** link again__
7. Go back to the **Hello World** app's **Versions** tab, and click on the link labeled **Install to Site** and choose your Weebly Developer Site
8. The Editor should immediately open, and you should see the `Hello World` element in the editor highlighted in blue
9. Drag the **Hello World** element on to a page of your Weebly site and play with the settings....TADA, hello world element in Weebly!

## Built With

* [Github](https://github.com)
* [Node.js](https://maven.apache.org/) - JavaScript runtime built on Chrome's V8 JavaScript Engine
* [NPM.js](https://npmjs.org) - Leading package manager for JavaScript
* [NVM](https://github.com/creationix/nvm) - Leading Node Version Manager

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on the Weebly Code of Conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial documentation work* - [PurpleBooth](https://github.com/PurpleBooth)
* **Benjamin Dean** - *Core Contributor* - [bdeanindy](https://github.com/bdeanindy)

## Contributors

* Submit a PR that is merged to see your name here!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Weebly Engineering Team for all their efforts
* Robin Whitmore - the initial author of the Weebly Developer Docs and reviewer making this app possible
* You, and all the Weebly App Developers who make Weebly awesome with your awesome questions and challenging issues
