# ExCL Developer Documentation #

### Contents ###

1. [Introduction to ExCL](#exclIntro)
- [WordPress](https://github.com/cmhouston/excl-cms#wordpress)
- [Titanium](#titanium)
	1. [Introduction to Titanium](#introToTitanium)
	- [Getting Started](#gettingStarted)
	- Build Process
		1. Walkthrough
		- Issues We've Run Into
	- Running the Unit Tests
	- Running the ExCL App
	- Code Overview
		1. Navigation Controller
		- Analytics
	- Enhancing the ExCL App
	- TiShadow
- Buildbox for Continuous Integration
- Deploying to the App Store
	1. Apple
	- Google Play

# <a name="exclIntro"></a> Introduction to ExCL #
ExCL is a platform that enables museums to engage visitors at museum activities through the use of a mobile application. Content is managed through a WordPress content management system by museum staff, and visitors will download the customized ExCL app, written using [Appcelerator Titanium](http://www.appcelerator.com/titanium/), to their mobile device. ExCL is also intended to be used by museums on kiosk devices and provides a kiosk mode for this purpose.

ExCL is divided into two parts: the content management system and the Appcelerator Titanium mobile application. This repository is for the Titanium mobile application. If you're interested in the content management side, click here to go to the [Wordpress project](https://github.com/cmhouston/excl-cms).

This documentation is intended for ExCL developers and details the steps to setup and enhance the mobile application. We will describe the Titanium technical details, followed by tips on using a continuous integration build server and deploying to the app stores.

# <a name="titanium"></a>Titanium #

## <a name="introToTitanium"></a> Introduction to Titanium ##

Titanium is a tool that allows developers to create applications for multiple platforms using a single project. For this project we are using Titanium in order to support both iOS and Android operating systems. 

Appcelerator provides many useful features and examples, which can be found under the [Titanium SDK Documentation](http://docs.appcelerator.com/titanium/3.0/) 

### <a name="gettingStarted"></a> Getting started ###

1. Clone the repository to your computer
2. Open up Titanium Studio and Import the existing project into your workspace
3. Start your development!



### Lib Docs ###

* [Navigation Controller](/docs/NavigationController.md)
* [Custom Calls API](/docs/CustomCalls.md)
* [Installing Unit Testing & Code Coverage Tools](/docs/installingUnitTestingAndCodeCoverageTools.md)
* [How to Debug on Genymotion](/docs/debuggingOnGenymotion.md)
