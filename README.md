<p align="center"><img width=50% src="https://user-images.githubusercontent.com/5436204/28038450-9c866638-65c7-11e7-9aee-f5277177404b.png"></p>

<p align="center">
<a href="https://github.com/raildock/raildock/network"><img src="https://img.shields.io/github/forks/raildock/raildock.svg" alt="GitHub forks"></a>
<a href="https://github.com/raildock/raildock/stargazers"><img src="https://img.shields.io/github/stars/raildock/raildock.svg" alt="GitHub stars"></a>
<a href="https://github.com/raildock/raildock/issues"><img src="https://img.shields.io/github/issues/raildock/raildock.svg" alt="GitHub issues"></a>
<a href="https://raw.githubusercontent.com/raildock/raildock/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="GitHub license"></a>
</p>

## Table Of Contents
* [Table Of Contents](#table-of-contents)
* [Basic Overview](#basic-overview)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Supported Software (Images)](#supported-software-images)
* [Changelog](#changelog)
* [Contributing](#contributing)
* [Contributors](#contributors)
* [License](#license)
* [Credits](#credits)

## Basic Overview
> Use Docker first and learn about it later.

***Raildock*** is a Docker development environment that facilitates running ***Ruby on Rails*** apps on Docker. Inspired by [Laradock](https://github.com/laradock/laradock).

## Requirements
- [Git](https://git-scm.com/downloads)
- [Docker](https://www.docker.com/community-edition) *>= 1.12*

## Installation
Installing Raildock is as easy as cloning the repository in the root of your Rails project.

    git clone https://github.com/raildock/raildock.git

If you are already using Git for your project:

    git submodule add https://github.com/raildock/raildock.git

## Usage
1. Enter the **raildock** folder and rename **env-example** to **.env**.

 ```cp env-example .env```

2. Open **.env** and configure the settings of the desired containers.

3. Run your containers:

 ```docker-compose up -d nginx mysql redis```

More detailed usage tutorial with examples is available at the [Wiki](https://github.com/raildock/raildock/wiki) page.

## Supported Software (Images)
* **Database Engines:** MySQL, PostgreSQL
* **Cache Engines:** Redis
* **Web Servers:** NGINX

**Raildock** introduces the [Workspace Image](https://github.com/raildock/workspace), as a development environment. It contains a rich set of helpful tools, all pre-configured to work and integrate with almost any combination of Containers and tools you may choose.

If you can’t find your Software [in the list](#supported-software-images), build it yourself and submit it. [Contributions](#contributing) are welcomed :)

## Changelog
To see what has changed in recent versions of **Raildock**, see the [CHANGELOG](https://github.com/raildock/raildock/blob/master/CHANGELOG.md).

## Problems
Please report and follow the resolution of any encountered problems in the [issue tracker](https://github.com/raildock/raildock/issues).

## Contributing
Thank you for considering contributing to **Raildock**. Any contributions are always welcomed as long as they follow the project's [contributing guidelines](https://github.com/raildock/raildock/blob/master/CONTRIBUTING.md).

## Contributors
* **Author:** [Veselin Stoyanov](https://github.com/veskoy)

## License
**Raildock** is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Credits
**Raildock** is inspired by and based on [Laradock](https://github.com/laradock/laradock).
