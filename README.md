# Config Management

Guidelines for Configuration Management using Git and Github

## Description

This document outlines the standards and process for configuration management

## Getting Started

### Dependencies

* Access to Github config_management repository will be required
* Team access to the config_management repository will be required

### Best Practices

* always first create your test branch from the config_production branch
* branch names should be as follow test_config_nameOfFeature
* always push the test banch you working on
* when creating the PR ensure you set to merge to the config_test branch
* always at a reviewer to your PR request

### Pre-Requisites 

* Ensure you have cloned the config managment repository to your local machine
* Any modifications needed to be made to files/folders

### Process Outline
* Copy Repository URL under code in the config_management repo
* Navigate to the directory you want to clone the repo to on your local machine
```
git clone git@github.com:hendrikthecodeblock/config_management.git
```
* Ensure you are on the config_production branch before creating a new branch
```
git checkout -b test_updatePrinterDriverFix
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
