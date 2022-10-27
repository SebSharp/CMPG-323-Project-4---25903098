# CMPG-323-Project-4---25903098
Testing & RPA using UiPath

## What is a RPA?

Robotic process automation (RPA) is a software technology that makes it easy to build, deploy, and manage software robots that emulate humans actions interacting with digital systems and software. Just like people, software robots can do things like understand what’s on a screen, complete the right keystrokes, navigate systems, identify and extract data, and perform a wide range of defined actions.

Source: <cite>https://www.uipath.com/rpa/robotic-process-automation</cite>

## Project 3
For Prject 3 we were expected to create a WebAppApp and host it on Azure where we are expected to understand architectural patterns as well as pay
specific attention to implementing coding principles and design patterns – aligning to the
requirements of the project.

## How to use the Project
The project can be accessed via this link hosted on Azure: https://25903098project3devicemanagementwebapp.azurewebsites.net/

The user would simply create an account (register), then they are able to view the online database of a Connected Office. This provides the user with a view of devices, zones and categories for this office. Users can then add. remove or edit any of the devices, categories or zones in the connected office.

This is done via API calls, managed by controllers each with their own Repository class and interface. These repositories get instantiated by a Generic repository ensuring that we follow proper design principles.

To check out the project, simply clone the repository. You will need to provide an AppSettings.json file containing the connection string. 
