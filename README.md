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
git checkout -b <test_config_nameOfFeature>
```
* Make the required changes or add new configuration files
* Once changes has been made commit your changes to your local git repo
```
git add .
git commit -m "Add fix for printer driver to config"
```
* Push your changes to github
```
git push origin <test_config_nameOfFeature>
```
* Create PR on github (NB ensure that you are merging into the test_config branch)
* Once All Tests has passed another PR will be created to merge into the config_production branch

## Version History

* 0.1
    * Initial Release


