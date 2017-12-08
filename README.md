# Lyfe-Contribution-Guidelines

# Contributing to Discover Lyfe
This document will go over what you can expect when contributing to Lyfe. It will highlight Lyfe's criteria for acceptable code. **Failure to adhere to these requirements will result in your code being rejected.**

----------

Example of Acceptable Code
-------------------
Please see the following repo for an example of acceptable code:

Effective Branch
-------------

All work must be done on a branch based on the latest 'development' branch. The branch name should be DEV_INITIALS-JIRA-TICKET#. For example, if John Smith was assigned the JIRA ticket, KH-19. All his work regarding this ticket will be committed to a branch named js-KH-19. 


Developing Code
-------------
All code must be developed in accordance with the JIRA workflow. Moreover, all code must be self-documenting (or well documented) and developed through test-driven development.

Use XIBs for Constraints
-------------------
All constraints of a view should be done with XIBs. Do NOT use code to create constraints. <a href="https://the-nerd.be/2015/08/07/load-assets-from-bundle-resources-in-cocoapods/">How to</a> properly use XIBs in pods.

Use Code for Styling UI Elements
-------------------
All styling (eg. background color, font, text color, etc.) should be done with code. Do NOT style elements using the interface builder.

No Storyboards
-------------------
Under NO circumstance will Storyboard files be accepted as contribution to Project PB

MVVM Design Pattern
-------------------
All code must use the MVVM Design Pattern. Please see the following link for more informaton: https://www.objc.io/issues/13-architecture/mvvm/

Coding styleguide
-------------------
All code must adhere to [Google's style guide](https://google.github.io/styleguide/objcguide.xml)

File Organization
-------------------
* UIElements Folder
	* elements of the page that have a custom class, separated into folders
* Models Folder
	* model files that encapsulate objects
* ViewModel Folder
	* all view model files of base view controller
* Base View Controller
