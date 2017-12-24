# ☕️ ristretto

> **Note:** This template doesn't come with all batteries included, but it does provide a basic template for rapid development. Here's a quick rundown:

## Key Features

* Completely Node setup
* Recommended `index.html` template
* Basic directory structure
* SCSS compilation and watching

### Install

Once the dependencies have been downloaded, you may download this repository. Alternatively, you can clone this repository using the following command:

```sh
$ git clone https://github.com/stefanmiodrag/ristretto
```

If you're using Laravel Valet as your development environment, make sure that the downloaded repository is in your serving sites  directory.

You’ll need node.js installed on your machine, you can download it on their website or, if you’re using Homebrew, you can install it by doing:

```sh
$ brew install node
```

Navigate to the site and install the node dependencies:

```sh
$ cd <sites directory>
# navigate to /sites directory
$ npm install
# install node dependencies from `package.json`
```

And you're all set! No need to configure anything else.

### Usage

Once that has finished installing, you’ll have to watch for changes made to .scss files. Run the following command:

```sh
$ npm run watch
# auto refreshes any changes made to .scss files in the /scss directory
# generated .css files will be located in the assets/css directory
```

By default, Valet serves your projects using the `.dev` extension. To visit the site, head to `<sites directory>.dev`.

## Licensing

This project is licensed under the terms of the MIT license. See the LICENSE.md file for more information.
