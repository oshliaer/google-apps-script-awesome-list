# Google Apps Script List
<!-- TOC depthFrom:2 -->

- [Resources](#resources)
  - [Useful sites & blogs](#useful-sites--blogs)
  - [Awesome code & things](#awesome-code--things)
- [Development](#development)
  - [Starter Kits](#starter-kits)
- [Libraries & Modules](#libraries--modules)
  - [Using databases](#using-databases)
  - [ORM (O/RM and O/R mapping tool)](#orm-orm-and-or-mapping-tool)
  - [Utility](#utility)
  - [Parsing](#parsing)
  - [oAuth](#oauth)
  - [Images & Pictures](#images--pictures)
- [Add-ons](#add-ons)
- [Testing](#testing)
- [Logging](#logging)
- [Snippets and assorted](#snippets-and-assorted)
  - [Snippets](#snippets)
  - [Assorted](#assorted)

<!-- /TOC -->
## Resources
* [Google Apps Script](https://plus.google.com/communities/102471985047225101769) G+ Community
* [Developing add-ons for Google Docs/Sheets/Forms](https://plus.google.com/u/0/communities/117193953428311185494) G+ Community
* Search by label  [[google-apps-script]](https://github.com/search?q=topic%3Agoogle-apps-script) on GitHub
* SO [[google-apps-script]](http://stackoverflow.com/questions/tagged/google-apps-script) tag
* Medium [Google Apps Script](https://medium.com/tag/google-apps-script) tag

### Useful sites & blogs
* [ctrlq.org](https://ctrlq.org/dev/google-apps-script) Amit Agarwal's site
* [mashe.hawksey.info](https://mashe.hawksey.info/category/google/google-apps-script) Martin Hawksey's site
* [ramblings.mcpher.com](http://ramblings.mcpher.com/) Desktop Liberation - the definitive resource for Google Apps Script and Microsoft Office automation
* [googleappscripting.com](http://googleappscripting.com) Google Apps Script Tutorials and Examples • Making Google Apps Script Accessible to Eveybody
* [scriptsexamples](https://sites.google.com/site/scriptsexamples/custom-methods) A set of code samples and libraries to foster programming in Google AppsScript to be easy.
* [tanaikech.github.io](https://tanaikech.github.io/tags/google-apps-script/) The `Google Apps Script` tag of the Kanshi's blog
* [andrewroberts.net](http://www.andrewroberts.net) The Andrew Roberts's site
* [kutil.org](http://www.kutil.org/search/label/google%20apps%20script) The `google apps script` tag of Ivan Kutil's blog

### Awesome code & things
* [Making a virtual machine in Google Sheets](http://briansteffens.com/2017/07/03/google-sheets-virtual-machine.html)
* [Easy data scraping with Google Apps Script in 5 minutes](http://www.kutil.org/2016/01/easy-data-scrapping-with-google-apps.html)

## Development
* [google/clasp](https://github.com/google/clasp) Develop Apps Script projects locally using clasp (Command Line Apps Script Projects) CLI.
* [gas-local](https://github.com/mzagorny/gas-local) [![GitHub stars](https://img.shields.io/github/stars/mzagorny/gas-local.svg?style=social&label=Star)](https://github.com/mzagorny/gas-local) Execute and test your google app scripts locally in node.js
* [gamified_journal](https://github.com/brainysmurf/gamified_journal) [![GitHub stars](https://img.shields.io/github/stars/brainysmurf/gamified_journal.svg?style=social&label=Star)](https://github.com/brainysmurf/gamified_journal) Proof of concept of a local development / push toolchain for Google Apps Scripting
* [gas-github](https://github.com/leonhartX/gas-github) [![GitHub stars](https://img.shields.io/github/stars/leonhartX/gas-github.svg?style=social&label=Star)](https://github.com/leonhartX/gas-github) Chrome-extension to manage Google Apps Script(GAS) code with github/github enterprise
* [ggsrun](https://github.com/tanaikech/ggsrun) [![GitHub stars](https://img.shields.io/github/stars/tanaikech/ggsrun.svg?style=social&label=Star)](https://github.com/tanaikech/ggsrun) This is a CLI tool to execute Google Apps Script (GAS) on a terminal
* [gdrive](https://github.com/prasmussen/gdrive) [![GitHub stars](https://img.shields.io/github/stars/prasmussen/gdrive.svg?style=social&label=Star)](https://github.com/prasmussen/gdrive) Google Drive CLI Client
* [MaartenDesnouck/google-apps-script](https://github.com/MaartenDesnouck/google-apps-script) [![GitHub stars](https://img.shields.io/github/stars/MaartenDesnouck/google-apps-script.svg?style=social&label=★)](https://github.com/MaartenDesnouck/google-apps-script) gas, for locally developing Google Apps Script projects
* [gas-lib](https://www.npmjs.com/package/gas-lib) [![npm](https://img.shields.io/npm/dt/gas-lib.svg)](https://www.npmjs.com/package/gas-lib) NPM package to add code auto-completion for Google AppsScript in your prefered code editor
* [AppsScriptColor](https://chrome.google.com/webstore/detail/appsscript-color/ciggahcpieccaejjdpkllokejakhkome) *(3 700+ users)* This Chrome extension provide 2 dark color themes for the google apps script editor. It also allows to use folders to sort your files more cleanly

### Starter Kits
* [apps-script-starter](https://github.com/labnol/apps-script-starter) A starter kit for building Google Apps Script projects with modern JavaScript ES6, Webpack, Babel and ESLint inside Visual Studio Code.
* [gas-minimal-boilerplate](https://github.com/asciian/gas-minimal-boilerplate) A minimal boilerplate with webpack for Google Apps Script
* [google-apps-script-template](https://github.com/nirazul/google-apps-script-template) A feature rich task runner for Google Apps Script to write, lint and push modern code to your documents
* [gas-shell](https://github.com/JeanRemiDelteil/gas-shell) [![GitHub stars](https://img.shields.io/github/stars/JeanRemiDelteil/gas-shell.svg?style=social&label=★)](https://github.com/JeanRemiDelteil/gas-shell) Starter template to develop locally Google AppsScript project with your prefered code editor (include build and publish as Add-on commands)

## Libraries & Modules

### Using databases
* [FirebaseApp](https://github.com/RomainVialard/FirebaseApp) [![GitHub stars](https://img.shields.io/github/stars/RomainVialard/FirebaseApp.svg?style=social&label=Star)](https://github.com/RomainVialard/FirebaseApp) The Google Apps Script binding for the Firebase Realtime Database
* [oshliaer/alasqlgs](https://github.com/oshliaer/alasqlgs) [![GitHub stars](https://img.shields.io/github/stars/oshliaer/alasqlgs.svg?style=social&label=Star)](https://github.com/oshliaer/alasqlgs) AlaSQLGS is a library that enables the use of the AlaSQL.js library in Google Apps Script

### ORM (O/RM and O/R mapping tool)
* [Goodel](https://github.com/7imon7ays/Goodel) [![GitHub stars](https://img.shields.io/github/stars/7imon7ays/Goodel.svg?style=social&label=Star)](https://github.com/7imon7ays/Goodel) An ORM for Google Apps scripts
* [gs-spreadsheet-manager](https://github.com/jsoma/gs-spreadsheet-manager) [![GitHub stars](https://img.shields.io/github/stars/jsoma/gs-spreadsheet-manager.svg?style=social&label=Star)](https://github.com/jsoma/gs-spreadsheet-manager) A slightly more object-oriented, ORM-y, and altogether pleasant way of dealing with Google Spreadsheets when using Google Apps Script
* [Sheetfu](https://github.com/socialpoint-labs/sheetfu) [![GitHub stars](https://img.shields.io/github/stars/socialpoint-labs/sheetfu.svg?style=social&label=Star)](https://github.com/socialpoint-labs/sheetfu) An ORM to treat spreadsheet as database tables using Google Apps Scripts. 
* [itmammoth/Tamotsu](https://github.com/itmammoth/Tamotsu) Object-Spreadsheet Mapping for Google Apps Script

### Utility
* [gas-underscore](https://github.com/simula-innovation/gas-underscore) [![GitHub stars](https://img.shields.io/github/stars/simula-innovation/gas-underscore.svg?style=social&label=Star)](https://github.com/simula-innovation/gas-underscore) Underscore for Google Apps Script
* [lodashgs](https://github.com/oshliaer/lodashgs) [![GitHub stars](https://img.shields.io/github/stars/oshliaer/lodashgs.svg?style=social&label=Star)](https://github.com/oshliaer/lodashgs) Lodash for Google Apps Script is a library that enables the use of the lodash.js library in Google Apps Script
* [brucemcpherson/cUseful](https://github.com/brucemcpherson/cUseful) [![GitHub stars](https://img.shields.io/github/stars/brucemcpherson/cUseful.svg?style=social&label=Star)](https://github.com/brucemcpherson/cUseful) Various dependency free useful functions
* [Gexpress](https://github.com/coderofsalvation/Gexpress) Express-ish middleware for google appscript (build NODEJS-ish  applications)

### Parsing
* [Apps-Script-htmlparser2-library](https://github.com/Spencer-Easton/Apps-Script-htmlparser2-library) [![GitHub stars](https://img.shields.io/github/stars/Spencer-Easton/Apps-Script-htmlparser2-library.svg?style=social&label=Star)](https://github.com/Spencer-Easton/Apps-Script-htmlparser2-library) A browserified version of fb55/htmlparser2 modified to work in Google Apps Script
* [cheeriogs](https://github.com/asciian/cheeriogs) [![GitHub stars](https://img.shields.io/github/stars/asciian/cheeriogs.svg?style=social&label=Star)](https://github.com/asciiann/cheeriogs) HTML manipulation library with jQuery-like interface.

### oAuth
* [apps-script-oauth2](https://github.com/googlesamples/apps-script-oauth2) [![GitHub stars](https://img.shields.io/github/stars/googlesamples/apps-script-oauth2.svg?style=social&label=Star)](https://github.com/googlesamples/apps-script-oauth2) An OAuth2 library for Google Apps Script
* [brucemcpherson/cGoa](https://github.com/brucemcpherson/cGoa) [![GitHub stars](https://img.shields.io/github/stars/brucemcpherson/cGoa.svg?style=social&label=Star)](https://github.com/brucemcpherson/cGoa) OAuth2 for Apps Script in a few lines of code

### Images & Pictures
* [ImgApp](https://github.com/tanaikech/ImgApp) [![GitHub stars](https://img.shields.io/github/stars/tanaikech/ImgApp.svg?style=social&label=Star)](https://github.com/tanaikech/ImgApp) This is a library of image tools for Google Apps Script

## Add-ons
* [google-docs-add-on](https://github.com/Automattic/google-docs-add-on) [![GitHub stars](https://img.shields.io/github/stars/Automattic/google-docs-add-on.svg?style=social&label=Star)](https://github.com/Automattic/google-docs-add-on) Publish to WordPress from Google Docs

## Testing
* [gast](https://github.com/zixia/gast) [![GitHub stars](https://img.shields.io/github/stars/zixia/gast.svg?style=social&label=Star)](https://github.com/zixia/gast) Google Apps Script TAP Testing-framework
* [GSUnit](https://sites.google.com/site/scriptsexamples/custom-methods/gsunit) is a Google Apps Script based testing framework based on JUnit by Kent Beck and JSUnit by Edward Hieatt. It will allow one to run tests while developing
* [classroomtechtools/modularLibraries.gs/UnitTesting](https://github.com/classroomtechtools/modularLibraries.gs/tree/master/UnitTesting) 
Assertion and unit testing of modular libraries

## Logging
* [gasl](https://github.com/zixia/gasl) [![GitHub stars](https://img.shields.io/github/stars/zixia/gasl.svg?style=social&label=Star)](https://github.com/zixia/gasl) Google Apps Script Logging-framework

## Snippets and assorted
### Snippets
* [A function to convert an XML string to a JSON object in Apps Script, using logic similar to the sunset method Xml.parse()](https://gist.github.com/erickoledadevrel/6b1e9e2796e3c21f669f)
### Assorted
* [GoogleSheets](https://github.com/Max-Makhrov/GoogleSheets) [![GitHub stars](https://img.shields.io/github/stars/Max-Makhrov/GoogleSheets.svg?style=social&label=Star)](https://github.com/Max-Makhrov/GoogleSheets) best code I've tested in Google Sheets
* [google-apps-script-snippets](https://github.com/oshliaer/google-apps-script-snippets) [![GitHub stars](https://img.shields.io/github/stars/oshliaer/google-apps-script-snippets.svg?style=social&label=Star)](https://github.com/oshliaer/google-apps-script-snippets) Google Apps Script Snippets
* [google-docs](https://github.com/fastfedora/google-docs) [![GitHub stars](https://img.shields.io/github/stars/fastfedora/google-docs.svg?style=social&label=Star)](https://github.com/fastfedora/google-docs) Libraries and functions used within Google Docs
* [youtube/api-samples/apps-script](https://github.com/youtube/api-samples/tree/master/apps-script/snippets) The youtube-data-api.gs file in this directory contains code snippets that are generated by the Data API code snippet tool at: https://developers.google.com/youtube/v3/code_samples/code_snippets
* [google/google-apps-script-samples](https://github.com/google/google-apps-script-samples) [![GitHub stars](https://img.shields.io/github/stars/google/google-apps-script-samples.svg?style=social&label=Star)](https://github.com/google/google-apps-script-samples) Various sample code and projects for the Google Apps Script platform
* [googlesamples/apps-script-templates](https://github.com/googlesamples/apps-script-templates) [![GitHub stars](https://img.shields.io/github/stars/googlesamples/apps-script-templates.svg?style=social&label=Star)](https://github.com/googlesamples/apps-script-templates) This repository contains a number of code templates for Google Apps Script that provide example frameworks for Apps Script projects
* [derekantrican/Google-Apps-Script-Library](https://github.com/derekantrican/Google-Apps-Script-Library) [![GitHub stars](https://img.shields.io/github/stars/derekantrican/Google-Apps-Script-Library.svg?style=social&label=Star)](https://github.com/derekantrican/Google-Apps-Script-Library) A variety of functions/programs written for Google Apps Script and Google services
* [stardotbmp/google-sheet-functions](https://github.com/stardotbmp/google-sheet-functions) [![GitHub stars](https://img.shields.io/github/stars/stardotbmp/google-sheet-functions.svg?style=social&label=Star)](https://github.com/stardotbmp/google-sheet-functions) A single repository for open sharing of custom functions I have found to be useful generally.
* [googlesamples/apps-script](https://github.com/googlesamples/apps-script) Sample code for Google Apps Script, a cloud-based scripting service for Google Apps
* [An Example of using an HTML form (e.g: "Contact Us" on a website) to send Email without a Backend Server (using a Google Script)](https://github.com/dwyl/html-form-send-email-via-google-script-without-server)
