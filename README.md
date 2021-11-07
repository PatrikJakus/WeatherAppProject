# WeatherApp User Documentation
© 2021 Easy Scrum Easy Go

##### Revision History
Date        | Revision | Description | Author
------------ | ------------ | ------------ | ------------ 
03/11/2021 | 1.0 | Initial user documentation | Colby 
05/11/2021 | 1.1 | Updated to include web-hosted info | Colby
07/11/2021 | 1.2 | Downloadable .exe related information | Colby

## Table of Contents

1. [Introduction](#Introduction)
2. [Product Features](#Product-Features)
	1. [Displays continent and city of user](#Displays-continent-and-city-of-user)
	2. [Displays animated media corresponding to weather type](#Displays-animated-media-corresponding-to-weather-type)
	3. [Temperature Scale is changeable suited to user preference](#Temperature-Scale-is-changeable-suited-to-user-preference)
3. [How do I?](#How-do-I?)
	1. [Change the temperature scale?](#Change-the-temperature-scale?)
	2. [Refresh the information displayed?](#Refresh-the-information-displayed?)
	3.  [Download the application?](#Download-the-application?)
4. [FAQ](#FAQ)
	1. [Why won’t my location show?](#Why-won’t-my-location-show?)
	2. [Why won’t the temperature show?](#Why-won’t-the-temperature-show?)
	3. [Where does the information provided come from?](#Where-does-the-information-provided-come-from?)
5. [Nonfunctional Requirements](#Nonfunctional-Requirements)
	1. [Storage](#Storage)
	2. [Compatibility](#Compatibility)
6. [Other Documentation](#Other-Documentation)

### Introduction
The Easy Scrum Easy Go WeatherApp is an application that provides accurate weather forecasting and simple on-demand information to its users. The application utilises an advanced API (application programming interface) which provides on-demand information to the user specific to their location given that permissions are authorised to allow action to do so.

### Product Features
Upon running the application it will automatically communicate and fetch the relevant weather information based upon the user’s specific location. As long as geolocation services have been authorised on the local machine (or browser if using the web hosted version), this will be seamless. 

#### Displays continent and city of user
This process will be automatically run and then the continent and city of the user will be displayed once the information has been gathered via the API.

#### Displays animated media corresponding to weather type
This process will be automatically run and then the corresponding media will be displayed according to weather type and information fetched by the API.

#### Temperature Scale is changeable suited to user preference
The user is able to change the temperature scale via left mouse-click between Celcius and Fahrenheit.

### How do I?
This section will explain to the user how to complete specific feature related objectives that may not be so easily identifiable. 

#### Change the temperature scale?
If you would like to change the temperature scale between Celcius and Fahrenheit, simply use your mouse and left-click over the displayed temperature. You can cycle between the two options at your discretion.

#### Refresh the information displayed?
The application does not automatically refresh, new information is retrieved every time the application is run. Therefore, if you would like to see current or updated weather information, please close and re-run the application.

#### Download the application?
If you wish to download the .exe to use on your local machine, you may do so by visiting https://weatherappprojectpurplebeard.co.uk/ and clicking the link at the bottom of the page. This will give you another option if you find our website to be unresponsive.

## FAQ
#### Why won’t my location show?
Please ensure geolocation services are enabled and authorised in order for the application to be able to retrieve the correct information.

#### Why won’t the temperature show?
Please ensure geolocation services are enabled and authorised in order for the application to be able to retrieve the correct information.

#### Where does the information provided come from?
Visual Crossing Web Services API of which provides real time weather information is utilised in WeatherApp.

## Nonfunctional Requirements

#### Storage
If you are using the downloadable application then WeatherApp1.0 requires 14mb of space on your local storage device.

#### Compatibility
Currently WeatherApp works with Windows 10 64bit operating system.

#### Other Documentation
Apart from the current ‘User Documentation’ there is also the following available to view here:

- Design Documentation
- Test Documentation
- System Documentation
- Installation Guide
- Release Report
