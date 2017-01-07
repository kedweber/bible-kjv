
# King James Reader: an Offline-First Approach

## Product Description
   
A multi-platform mobile and browser app for reading the contents of a book; namely, the King James version of the Bible. 
The focus of this app is to maximize both Offline-First and Mobile first design approaches. For technical details, see 
the Project Description below.

## History of the KJV
   
In 1604, King James I of England authorized that a new translation of the Bible into English be started. It was finished in 1611, just 85 years after the first translation of the New Testament into English appeared (Tyndale, 1526). The Authorized Version, or King James Version (KJV), quickly became the standard for English-speaking Protestants. Its flowing language and prose rhythm has had a profound influence on the literature of the past 400 years. The King James Version present on the Bible Gateway matches the 1987 printing. The KJV is public domain in the United States.

## Downloads [Mobile Apps not yet released]

[![Build Status][circle-badge]][circle-badge-url]
[![Build status][appveyor-badge]][appveyor-badge-url]
[![npm][npm-badge]][npm-badge-url]

## Project Description
   
This project is currently at it's infancy. Personally, I do not like to publish public repositories where I am 
building everything from the ground up; however, the development of this project has already ran into problems where 
it behoves us to incorporate the use of software version control.

There are 66 books in the Bible, all with varying numbers of chapters. This project is not promoting the King James' 
translation of the Bible over any other version. The choice of versions was simple when the copyright on this 1611 
publication recently ran out.

When you're not so tired, you really should explain why we chose Ionic, Angular, TypeScript and much more to 
facilitate cross-platform deployment.

## Business Solutions with Related Technology

Many individuals are unaware of the growing (said in 2017) popularity of the technology incorporated in this project. 
This section is for those individuals and anyone with a keen interest in real-world implementations.

 *  [Diesel](http://store.diesel.com/) used the designers at [MobileCaddy.net](mobilecaddy.net) to build a 
 [merchandising app](http://www.mobilecaddy.net/diesel-achieving-digital-business-transformation-mobilecaddy/) to analyze 
 the product and stores performances. They also incorporated the [Salesforce Mobile SDK](http://salesforce.com), 
 to reduce time for user authentication. Personal note, Ionic does include a built in identification within their 
 [Ionic Cloud Client](http://github.com/driftyco/ionic-cloud) component; originally named `ionic-platform-web-client`.
 *  [Smithsonian National Museum of African American History & Culture](https://nmaahc.si.edu/) hired the D.C. based designers at  
[Clearly Innovative](http://www.clearlyinnovative.com/nmaahc-mobile-app) to build their 
[app](https://nmaahc.si.edu/connect/mobile/apps) to browse their museum in the IoT. Ionic 2 and Angular were used 
to develop the browsing app and a Content Management System within a single codebase for both Mac iOS and Android.
 *   At the beginning of 2017 [In3](http://www.in3dc.com/) will be opening Washington, D.C.'s first community space, in Shaw, 
dedicated to inclusion, innovation and incubation. **Ionic studies** will be in [Luma Lab's](http://www.luma-lab.com/) 
curriculum to spur the next generation of developers in the direction of Ionic, Angular and Cordova technologies.
 *  WordPress related software-house [AppPresser](https://apppresser.com/) has begun to use Ionic 2 in order 
 to turn WordPress and Ionic into a Dynamic Duo. With the final release of Ionic 2, as well as the REST API being included 
 in WordPress 2.7's core, it’s getting even easier to integrate WordPress into mobile apps. Ionic's blog has a good example 
 of using [WP-API to include Wordpress](http://blog.ionic.io/the-dynamic-duo-wordpress-and-ionic-2/) in your applications.
 *  [Joule](https://www.chefsteps.com/joule) is an immersion circulator (see below) that allows you to use the sous vide 
 cooking method, in which food is placed in airtight plastic bags, then heated in precisely controlled, low-temperature 
 water. Because the food can never get hotter than the water, it’s almost impossible to under- or overcook it, 
 guaranteeing some of the most amazing steak, fish or chicken you have ever had. Joule’s companion app is built with Ionic.
 A thermal immersion circulator is an electrically powered device that circulates and heats a warm fluid kept at an 
 accurate and stable temperature.
 *  [Watch for more Use Cases on Ionic's blog](http://blog.ionic.io/). Certainly, to be continued...
 

### Notes


| Version | Language | Size | Compressed |
|---|---|---|---|
| King James 1611 | English | 5932779 or 5.9 Mb | 1534415 or 1.5 Mb |
| Luther 1545 | German | 6114176 or 6.1 Mb | 1630993 or 1.6 Mb |
| Bahasa Sehari-hari | Indonesian | 6262069 or 6.3 Mb | 1620795 or 1.6 Mb |

<!--
ls -FaGl res/js/kjv-*.json | awk '{ total += $5 } END { print total }'
-->

[mobilecaddy.net]: https://www.mobilecaddy.net/


[circle-badge]: https://circleci.com/gh/driftyco/ionic-cli.svg?style=shield
[circle-badge-url]: https://circleci.com/gh/driftyco/ionic-cli
[appveyor-badge]: https://ci.appveyor.com/api/projects/status/oqaqa7fdc7y9mma3?svg=true
[appveyor-badge-url]: https://ci.appveyor.com/project/jthoms1/ionic-cli
[npm-badge]: https://img.shields.io/npm/v/ionic.svg
[npm-badge-url]: https://www.npmjs.com/package/ionic