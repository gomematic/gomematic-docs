# Gomematic: Documentation

[![Build Status](http://github.dronehippie.de/api/badges/gomematic/gomematic-docs/status.svg)](http://github.dronehippie.de/gomematic/gomematic-docs)
[![Stories in Ready](https://badge.waffle.io/gomematic/gomematic-api.svg?label=ready&title=Ready)](http://waffle.io/gomematic/gomematic-api)
[![Join the Matrix chat at https://matrix.to/#/#gomematic:matrix.org](https://img.shields.io/badge/matrix-%23gomematic%3Amatrix.org-7bc9a4.svg)](https://matrix.to/#/#gomematic:matrix.org)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/673d5717db584f9dbc0671e60c1aa62a)](https://www.codacy.com/app/gomematic/gomematic-docs?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=gomematic/gomematic-docs&amp;utm_campaign=Badge_Grade)

**This project is under heavy development, it's not in a working state yet!**

Documentation for the Gomematic API and the command line client, you can find this website at [gomematic.webhippie.de](https://gomematic.webhippie.de).


## Hosting

The website is hosted on [Netlify](https://www.netlify.com/), the website gets automatically updated on every push to the `master` branch.


## Install

This website uses the [Hugo](https://github.com/spf13/hugo) static site generator. If you are planning to contribute you'll want to download and install Hugo on your local machine. The installation of Hugo is out of the scope of this document, so please take the [official install instructions](https://gohugo.io/overview/installing/) to get Hugo up and running.


## Development

To generate the website and serve it on [localhost:1313](http://localhost:1313) just execute this command and stop it with `Ctrl+C`:

```bash
make server
```

When you are done with your changes just create a pull request, after merging the pull request the website will be updated automatically.


## Security

If you find a security issue please contact gomematic@webhippie.de first.


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)


## License

CC-BY-SA-4.0


## Copyright

```
Copyright (c) 2018 Thomas Boerger <thomas@webhippie.de>
```
