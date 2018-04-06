<p align="center">
  <img src="https://raw.githubusercontent.com/Chappted/RAML-API-Docs/stable/icon.png"
      width=400 height=400 alt="Chappted Icon">
</p>

<p align="center">
    <a href="https://www.bitrise.io/app/<TODO>">
        <img src="https://www.bitrise.io/app/<TODO>.svg?token=<TODO>&branch=stable"
             alt="Build Status">
    </a>
    <img src="https://img.shields.io/badge/RAML-1.0-FFAC45.svg"
         alt="RAML: 1.0">
    <a href="https://github.com/Chappted/RAML-API-Docs/blob/stable/LICENSE.md">
        <img src="https://img.shields.io/badge/License-GPL--3.0-lightgrey.svg"
             alt="License: GPL-3.0">
    </a>
</p>

<p align="center">
    <a href="#about">About</a>
  • <a href="https://github.com/Chappted/RAML-API-Docs/issues">Issues</a>
  • <a href="#">Generated Docs (in progress)</a>
  • <a href="#contributing">Contributing</a>
  • <a href="#license">License</a>
</p>


## About

Challange Accepted! Search, create or participate challanging events with your friends or people you just met.

This repo includes the Chappted RAML-API-Docs. You can find other parts of the Chappted project [here](https://github.com/Chappted).


## Development

### Getting Started

This API documentation follows the [RAML](https://github.com/raml-org/raml-spec/blob/master/versions/raml-10/raml-10.md/) API specification language. It is recommended to install the [API Workbench](http://apiworkbench.com) for editing and [raml2html](https://github.com/raml2html/raml2html) for generating HTML files.

The command to generate the docs (once the above are installed) is:

```
raml2html api.raml > api.html && open api.html
```


## Contributing

Contributions are welcome. Feel free to open an issue on GitHub with your ideas or implement an idea yourself and post a pull request. If you want to contribute code, please try to follow the same syntax and semantic in your **commit messages** (see rationale [here](http://chris.beams.io/posts/git-commit/)).

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/Chappted/RAML-API-Docs/blob/stable/CONDUCT.md). By participating in this project you agree to abide by its terms.


## License

This project is released under the [GNU General Public License, version 3 (GPL-3.0)](http://opensource.org/licenses/GPL-3.0).
