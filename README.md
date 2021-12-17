# Finepak
Flatpak-ing Microsoft Windows applications with Wine.

## Why fork?
This is a fork of [winepak](https://github.com/winepak), the reason why I wanted to fork is because that project is dead. The last commit was in 2018

## Goals
* Package `wine` applications via `flatpak`
* Make installing and running applications Just Work<sup>TM</sup>

## Repos
* [finepak-sdk-images](https://github.com/finepak/finepak-sdk-images): The Sdk & Platform for `finepak`
* [applications](https://github.com/finepak/applications): A collection of flatpak manifest for building Microsoft Windows applications via `finepak`

### Building
To get started with finepak you first need to build & install the Sdk & Platform, instructions can be found on the [finepak-sdk-images](https://github.com/finepak/finepak-sdk-images) repo.

Next pick an application to build & install. A list of them with instructions can be found in the [applications](https://github.com/finepak/applications) repo. Take note of the Platform branch the application uses. Most games require the `staging` branch of Sdk/Platform.
