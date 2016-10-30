# Selenium
>Tool that bring us a set of commands to automatize web tests. Selenium could be programed on different languages.
Actually there are three platforms:
 
* Selenium 1, is deprecated and does not have support.
* Selenium 2, is the last version.
* Selenium IDE, is a firefox plugin that help us to make the web tests.

## Plataformas soportadas:

### Web driver:
* Google Chrome
* Internet Explorer 7, 8, 9, 10, and 11 on appropriate combinations of Vista, Windows 7, Windows 8, and Windows 8.1. As of April 15 2014, IE 6 is no longer supported. The driver supports running 32-bit and 64-bit versions of the browser where applicable
* Firefox: latest ESR, previous ESR, current release, one previous release
* Safari
* Opera
* HtmlUnit
* phantomjs
* Android (with Selendroid or appium)
* iOS (with ios-driver or appium)

## Selenium 1.0, Selenium RC

| Browser | Selenium IDE | Selenium 1(RC) | SO |
| ------- | ------------ | -------------- | -- |
| Firefox 3.x | Record and playback tests | Start browser, run tests | Windows, Linux, Mac |
| Firefox 3 | Record and playback tests | Start browser, run tests | Windows, Linux, Mac |
| Firefox 2 | Record and playback tests | Start browser, run tests | Windows, Linux, Mac |
| IE 8 | Test execution only via Selenium RC* | Start browser, run tests |	Windows |
| IE 7 | Test execution only via Selenium RC* | Start browser, run tests |	Windows |
| IE 6 | Test execution only via Selenium RC* | Start browser, run tests |	Windows |
| Safari 4 | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Mac |
| Safari 3 | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Mac |
| Safari 2 | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Mac |
| Opera 10 | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Linux, Mac |
| Opera 9 | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Linux, Mac |
| Opera 8 | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Linux, Mac |
| Google Chrome | Test execution only via Selenium RC |	Start browser, run tests |	Windows, Linux, Mac |
| Others | Test execution only via Selenium RC |	Partial support possible |	As applicable |

# Selenium IDE
Selenium IDE is an development integrated enviroment to make tests.

## Requisitos:
* Firefox

## Instalation
* Desde add-ons de Mozilla Firefox
* Ref. [instalation](http://www.seleniumhq.org/download/) 

## Técnicas para desarrollar tests
* Recording
* Adding Verifications and Asserts With the Context Menu
* Editing

## Running test cases
* Run test case
* Run test suite
* Stop and start
* Stop in the middle
* Start from the middle
* Run any single command

## Selenium commands
* Actions
* Accessors
* Assertions

## Commonly used  Selenium commands
* Open
* Click/clickAndWait
* verifyTitle/assertTitle
* verifyTextPresent
* verifyElementPresent
* verifyText
* verifyTable
* waitForPageToLoad
* waitForElementPresent

## Locating page elements
* by identifier
* by name
* by xpath
* by DOM
* by css

## Patterns
* Globbing patterns
* Regular expresión patterns
* Exact patterns

## We can work with :
* Alerts
* Pop-ups
* Multiple Windows
* Debugging

# Selenium web driver
>WebDriver is a web automation framework that allows you to execute your tests against different browsers, not just Firefox (unlike Selenium IDE). WebDriver also enables you to use a programming language in creating your test scripts (not possible in Selenium IDE).
Ref. [Selenium](http://www.guru99.com/introduction-webdriver-comparison-selenium-rc.html)


![image](http://cdn.guru99.com/images/WebDriver_and_Browsers(1).jpg)
    
## Following programming languages, are supported by WebDriver
* Java
* C#
* PHP
* Python
* Perl
* Ruby
* JavaScript

# Selenium RC
![image](http://www.seleniumhq.org/selenium-rc.png)

## Requirements
* Java 1.5 or later
* PATH enviroment variable

## Languages
* Java
* C#
* Python
* Ruby
* Perl, PHP

## Architecture
![image](http://www.seleniumhq.org/docs/_images/chapt5_img02_Architecture_Diagram_1.png)

Heightened priviliges browsers

![image](http://www.seleniumhq.org/docs/_images/chapt5_img02_Architecture_Diagram_2.png)

# Test Design considerations

## Test types
* Content test
* Testing links
* Function tests
* Testing dynamic elements
* Ajax tests
* Data driven testing
* Database validation

# Selenium Grid
>Selenium-Grid allows you run your tests on different machines against different browsers in parallel.
When use it:
* To run your tests against multiple browsers, multiple versions of browser, and browsers running on different operating systems.
* To reduce the time it takes for the test suite to complete a test pass.

## Instalation
>Does not need. it’s a single jar file.

# User extensions
>Extending Selenium by adding your own actions, assertions and locator-strategies can be quite simple. Add JavaScript methods to the Selenium object prototype and the PageBot object prototype.

# Selenium RC or Web Driver

## Why Migrate to WebDriver
>Moving a suite of tests from one API to another API requires an enormous amount of effort. Why would you and your team consider making this move? Here are some reasons why you should consider migrating your Selenium Tests to use WebDriver.
* Smaller, compact API. WebDriver’s API is more Object Oriented than the original Selenium RC API. This can make it easier to work with.
* Better emulation of user interactions. Where possible, WebDriver makes use of native events in order to interact with a web page. This more closely mimics the way that your users work with your site and apps. In addition, WebDriver offers the advanced user interactions APIs which allow you to model complex interactions with your site.
* Support by browser vendors. Opera, Mozilla and Google are all active participants in WebDriver’s development, and each have engineers working to improve the framework. Often, this means that support for WebDriver is baked into the browser itself: your tests run as fast and as stably as possible.

# Contributors
Keneth Ubeda
location: Guatemala, Guatemala city.
