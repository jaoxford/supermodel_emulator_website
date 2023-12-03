# Supermodel Website

Website for the Supermodel emulator.

## Table of Contents

- [Prerequisites](#prerequisites)
- [About](#about_the_project)
- [Usage](#usage)
- [Contributing](#contributing)

## About The Project

This project aims to modernise and rebuild the website of the Supermodel emulator using modern tools and technology. Making it easy for non-technical people to update and maintain.

### Built With

![Hugo](https://img.shields.io/badge/Hugo-black.svg?style=for-the-badge&logo=Hugo)

[(back to top)](#table-of-contents)

## Prerequisites

To build this project from scratch you'll need to [install hugo](https://gohugo.io/installation/):

[(back to top)](#table-of-contents)

## Usage

### Blog posts

To add a new blog post :

```shell
hugo new content blog/<blog_post_title>.md
```

This will generate a blog post based on the `blog.md` archetype in the `archetypes` directory.
The generated blog post will be located in the `content/blog/` directory

### Game Compatibility

To add a new page regarding game compatibility do:

```shell
hugo new content compatibility/<game_title>.md
```

This will generate a game compatibility page based on the `compatibility.md` archetype in the `archetypes` directory.
The generated compatibility page will be located in the `content/compatibility/` directory

### Building Locally

To build and serve the site locally do:

```shell
hugo server --noHTTPCache
```

The `--noHTTPCache` option is useful since you'll be reloading the site, and preventing HTTP caching is useful when there are multiple reloads happening.

[(back to top)](#table-of-contents)

### Building for a Website

To generate the outputs for the actual website you'll need to run a different command:

```shell
hugo
```

This will generate everything into the `public/` directory. Which can then be transferred into the hosting / web server.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

[(back to top)](#table-of-contents)
