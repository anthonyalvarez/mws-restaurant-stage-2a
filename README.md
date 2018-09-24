# Product Name
mws-restaurant-stage-2a

## Table of Contents

1. [Specification](#Specification)
1. [Requirements](#Requirements)
1. [Technology](#Technology)
1. [Getting Started](#Getting-Started)
1. [Versioning](#Versioning)
1. [License](#license)
1. [Contact](#Contact)

## Specification

You will be provided code for a Node development server and a README for getting the server up and running locally on your computer. The README will also contain the API you will need to make JSON requests to the server. Once you have the server up, you will begin the work of improving your Stage One project code.

The core functionality of the application will not change for this stage. Only the source of the data will change. You will use the fetch() API to make requests to the server to populate the content of your Restaurant Reviews app.

For the Restaurant Reviews projects, you will incrementally convert a static webpage to a mobile-ready web application. In Stage Two, you will take the responsive, accessible design you built in Stage One and connect it to an external JSON REST API server.

1. Use asynchronous JavaScript to request JSON data from the server. 

2. Store data received from the server in an offline database using IndexedDB, which will create an app shell architecture.

3. Finally, you’ll work to optimize your site to meet performance benchmarks, which you’ll test using Lighthouse.

***[Back to top](#table-of-contents)***

## Requirements

Use server data instead of local memory In the first version of the application, all of the data for the restaurants was stored in the local application. You will need to change this behavior so that you are pulling all of your data from the server instead, and using the response data to generate the restaurant information on the main page and the detail page.

Use IndexedDB to cache JSON responses In order to maintain offline use with the development server you will need to update the service worker to store the JSON received by your requests using the IndexedDB API. As with Stage One, any page that has been visited by the user should be available offline, with data pulled from the shell database.

Meet the minimum performance requirements Once you have your app working with the server and working in offline mode, you’ll need to measure your site performance using Lighthouse. 

Lighthouse measures performance in four areas, but your review will focus on three:

1. Progressive Web App score should be at 90 or better. 
1. Performance score should be at 70 or better.
1. Accessibility score should be at 90 or better.

You can audit your site's performance with Lighthouse by using the Audit tab of Chrome Dev Tools.

### Technology

* Progessive Web App (PWA)
* Responsive Web Design (RWD)
* Responsive Images
* ES6 / JavaScript 2015
* JavaScript Module bundling
* JavaScript Source Maps
* File Minification
* File Uglification
* Cross Browser Testing
* Grunt
* Gulp
* Indexed DB (IDB)
* Yeoman Web App Generator
* Bower Components
* Fetch API
* Cache API
* JSON REST API
* eslint
* Node
* NPM
* Lighthouse

***[Back to top](#table-of-contents)***

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
node
NPM
Git
```

### Dependencies
Refer to /package.json

### Development Setup
```sh
npm install
bower install
gulp serve
```
### API Reference
TODO: Write API Reference

### Usage
TODO: Write usage instructions

## Versioning

 Using [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/anthonyalvarez/mws-restaurant-stage-2a/tags).

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

***[Back to top](#table-of-contents)***

## Contributing

1. Fork it (<https://github.com/anthonyalvarez/mws-restaurant-stage-2a/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

**[Back to top](#table-of-contents)**

## License
Open source

**[Back to top](#table-of-contents)**

## Contact
- Anthony E. Alvarez – [My GitHub](https://github.com/anthonyalvarez/)
- Twitter: [@AnthonyEAlvarez](https://twitter.com/AnthonyEAlvarez)

**[Back to top](#table-of-contents)**
