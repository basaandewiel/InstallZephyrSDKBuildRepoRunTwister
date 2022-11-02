![Build qemu_x86](https://github.com/basaandewiel/InstallZephyrSDKBuildRepoRunTwister/actions/workflows/InstallZephyrSDKBuildTest.yml/badge.svg) 

# Overview

This repo is based on the standard Hello World sample. It is used to show how you can work with Github Actions to 
* Install Zephyr SDK (on Ubuntu:latest)
* Build the Zephyr repo for multiple targets
* Unit test the repo using Twister

# Executing Github actions
The Github actions are executed after triggering them either manually, or on push and pull request.

# Inner workings
Zephyr SDK is installed along with only the necessary toolchains.

There is a file `sample.yaml` that contains the tests to be executed via Twister. 
