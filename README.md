### Note
This is a fork of https://github.com/derskythe/WpfSettings.

It is meant to upgrade the original project to .NET 6 and to publish it as a nuget package for easy use.

The original README can be found below.

### Preface
This project was created as a wrapper for the ClickOnce in .NET 5, because in this version ApplicationDeployment was not implemented.

### Features

- Silent update
- Get current running version and version of package on server
- Get DataDir of installation

### Description
The main project is PureManApplicationDeployment and you can embed it into your application.
Unfortunately, I have not found a way to receive UpdateUrl so this property must be hardcoded.
The WpfSettings project is just an example of how you can work with the PureManApplicationDeployment library and shows main functionality.