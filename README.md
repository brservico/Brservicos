# [JoomGap Boilerplate](http://www.joomgap.com/)

JGBoilerplate: the simplest JoomGap app template.

JoomGap Boilerplate is a starter project to create a hybrid mobile app for Joomla! CMS, powered by Cordova/PhoneGap, AngularJS and Ionic.

This project is the product of many years of iterative development and
combined community knowledge from open source projects. It does not impose a specific development
philosophy or framework, so you're free to architect your code in the
way that you want.

* Homepage: [http://www.joomgap.com/](http://www.joomgap.com/)
* Source: [https://github.com/JoomGap/JGBoilerplate](https://github.com/JoomGap/JGBoilerplate)
* Twitter: [@JoomGap](https://twitter.com/JoomGap)

## Quick start

Choose one of the following options:

1. Download the latest stable release from
   [joomgap.com](http://www.joomgap.com/joomgap-boilerplate.html).
2. Or, clone the git repo — `git clone
   https://github.com/JoomGap/JGBoilerplate.git`
3. Create a new app in [PhoneGap build](https://build.phonegap.com).
4. Build and download APK (Android) or IPA (iOS) file.
5. Copy the file to your mobile phone and install it.
6. Have fun!

## How to integrate JG Boilerplate with Joomla! CMS

JG Boilerplate includes [JoomGap Simple Library](https://github.com/JoomGap/JGSimple) to integrate Joomla! CMS.

A call to Joomla! can be simply implemented in this way:

    q = JgSimpleResource.get(url, params).$promise;
z
    q.then(function(response) {
        if ( (response) && (response.success) ) {
            console.log(response.data);
        }
    });

> Even though JG Simple Library is included to open a connection to Joomla! CMS, it still requires a server-side service, with an API, to access and provide any functionality. For instance, [JG JEDStarter](http://www.joomgap.com/docs/basics/jedstarter) implements a similar app based on JED's "Install from Web" service.

## Features

* Cordoba/PhoneGap mobile application.
* Includes:
  * Cordoba/PhoneGap project
  * PhoneGap (iOS / Android / Windows)
  * [PhoneGap build](https://build.phonegap.com)-ready configuration
  * AngularJS
  * AngularJS Animate
  * AngularJS Resource
  * AngularJS Sanitize
  * AngularJS UI Router
  * [JoomGap Simple Library](https://github.com/JoomGap/JGSimple)
  * Ionic Framework
  * ngCordova

## Useful Commands

Start a local development server for app dev/testing.

	ionic serve	
	
Compile Saas to build stylesheets.

	gulp
	
Updating Ionic. Update bower.json, driftyco/ionic-bower#....

	gulp install

## Mobile operating system support

* Android 5 and 6
* Apple iOS 8 and 9

*This doesn't mean that JoomGap Boilerplate cannot be used in older OS,
just that we'll ensure compatibility with the ones mentioned above.*

## Screenshots

### Installation Step 1 - Android

![Installation Step 1 - Android](http://cdn.joomgap.com/images/JGBoilerplate/JGBoilerplate-1-install.jpg)

### Installation Step 2 - Android

![Installation Step 2 - Android](http://cdn.joomgap.com/images/JGBoilerplate/JGBoilerplate-2-install.jpg)

### Welcome screen - Android

![Welcome screen - Android](http://cdn.joomgap.com/images/JGBoilerplate/JGBoilerplate-3-start.jpg)

## License

The code is available under the [GNU GENERAL PUBLIC LICENSE Version 3](LICENSE).

## Feedback

We welcome feedback! Leave a comment by clicking the icon in upper right corner of the banner.

* [We are always open for a quick chat!](http://www.joomgap.com/more/contact-us.html)
* [Facebook](https://twitter.com/joomgap)
* [Twitter](https://www.facebook.com/joomgap)
* [RSS](http://www.joomgap.com/more/blog.feed?type=rss)
* Post issues and pull requests on JoomGap github repositories.

## Copyright

Copyright © 2007-2016 [Extly Extensions](http://www.extly.com/) - All Rights Reserved.

Joomla! name is used under a limited license from Open Source Matters in the United States and other countries. Extly.com is not affiliated with or endorsed by Open Source Matters or the Joomla! project.
