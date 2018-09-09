# Google Apps Script List

<!-- TOC depthFrom:2 -->

- [Resources](#resources)
  - [Useful sites & blogs](#useful-sites--blogs)
  - [Awesome code & things](#awesome-code--things)
  - [Lists](#lists)
- [Development](#development)
  - [Starter Kits](#starter-kits)
  - [Shims and polyfills](#shims-and-polyfills)
- [Libraries & Modules](#libraries--modules)
  - [Using databases](#using-databases)
  - [ORM (O/RM and O/R mapping tool)](#orm-orm-and-or-mapping-tool)
  - [Utility](#utility)
  - [Parsing](#parsing)
  - [oAuth](#oauth)
  - [Images & Pictures](#images--pictures)
- [Open Source Add-ons](#open-source-add-ons)
- [Testing](#testing)
- [Logging](#logging)
- [Snippets and assorted](#snippets-and-assorted)
  - [Snippets](#snippets)
    - [Lists & collections](#lists--collections)
    - [Spreadsheets](#spreadsheets)
    - [XML](#xml)
  - [Assorted](#assorted)

<!-- /TOC -->

## Resources

- [Google Apps Script](https://plus.google.com/communities/102471985047225101769) G+ Community
- [Developing add-ons for Google Docs/Sheets/Forms](https://plus.google.com/u/0/communities/117193953428311185494) G+ Community
- Search by label  [[google-apps-script]](https://github.com/search?q=topic%3Agoogle-apps-script) on GitHub
- SO [[google-apps-script]](http://stackoverflow.com/questions/tagged/google-apps-script) tag
- Medium [Google Apps Script](https://medium.com/tag/google-apps-script) tag

### Useful sites & blogs

- [ctrlq.org](https://ctrlq.org/dev/google-apps-script) Amit Agarwal's site
- [mashe.hawksey.info](https://mashe.hawksey.info/category/google/google-apps-script) Martin Hawksey's site
- [ramblings.mcpher.com](http://ramblings.mcpher.com/) Desktop Liberation - the definitive resource for Google Apps Script and Microsoft Office automation
- [googleappscripting.com](http://googleappscripting.com) Google Apps Script Tutorials and Examples • Making Google Apps Script Accessible to Eveybody
- [scriptsexamples](https://sites.google.com/site/scriptsexamples/custom-methods) A set of code samples and libraries to foster programming in Google AppsScript to be easy.
- [tanaikech.github.io](https://tanaikech.github.io/tags/google-apps-script/) The `Google Apps Script` tag of the Kanshi's blog
- [andrewroberts.net](http://www.andrewroberts.net) The Andrew Roberts's site
- [kutil.org](http://www.kutil.org/search/label/google%20apps%20script) The `google apps script` tag of Ivan Kutil's blog
- [googleappsscript.org](http://www.googleappsscript.org/) Google Apps Script Tutorial

### Awesome code & things

- [Making a virtual machine in Google Sheets](http://briansteffens.com/2017/07/03/google-sheets-virtual-machine.html)
- [Easy data scraping with Google Apps Script in 5 minutes](http://www.kutil.org/2016/01/easy-data-scrapping-with-google-apps.html)

### Lists

- [Learning Google Apps Script](https://gist.github.com/labnol/0b67f812a827fd9babc5) The best resources for learning Google Apps Script, the glue that connects GSuite services including Gmail, Google Drive, Calendar, Maps, Analytics and more.

[goto top ⇑](#google-apps-script-list)

## Development

- [google/clasp](https://github.com/google/clasp) Develop Apps Script projects locally using clasp (Command Line Apps Script Projects) CLI.
- [gas-local](https://github.com/mzagorny/gas-local) Execute and test your google app scripts locally in node.js
- [gamified_journal](https://github.com/brainysmurf/gamified_journal) Proof of concept of a local development / push toolchain for Google Apps Scripting
- [gas-github](https://github.com/leonhartX/gas-github) Chrome-extension to manage Google Apps Script(GAS) code with github/github enterprise
- [ggsrun](https://github.com/tanaikech/ggsrun) This is a CLI tool to execute Google Apps Script (GAS) on a terminal
- [gdrive](https://github.com/prasmussen/gdrive) Google Drive CLI Client
- [MaartenDesnouck/google-apps-script](https://github.com/MaartenDesnouck/google-apps-script) gas, for locally developing Google Apps Script projects
- [gas-lib](https://www.npmjs.com/package/gas-lib) NPM package to add code auto-completion for Google AppsScript in your prefered code editor
- [AppsScriptColor](https://chrome.google.com/webstore/detail/appsscript-color/ciggahcpieccaejjdpkllokejakhkome) *(3 700+ users)* This Chrome extension provide 2 dark color themes for the google apps script editor. It also allows to use folders to sort your files more cleanly

### Starter Kits

- [apps-script-starter](https://github.com/labnol/apps-script-starter) A starter kit for building Google Apps Script projects with modern JavaScript ES6, Webpack, Babel and ESLint inside Visual Studio Code.
- [gas-minimal-boilerplate](https://github.com/asciian/gas-minimal-boilerplate) A minimal boilerplate with webpack for Google Apps Script
- [google-apps-script-template](https://github.com/nirazul/google-apps-script-template) A feature rich task runner for Google Apps Script to write, lint and push modern code to your documents
- [gas-shell](https://github.com/JeanRemiDelteil/gas-shell) Starter template to develop locally Google AppsScript project with your prefered code editor (include build and publish as Add-on commands)
- [artnc/gas-es6-webpack](https://github.com/artnc/gas-es6-webpack) ES6+Webpack boilerplate for Google Apps Script
- [howdy39/gas-clasp-starter](https://github.com/howdy39/gas-clasp-starter) A starter template for Google Apps Script by clasp
- [zaki-yama/webpack-google-apps-script-template](https://github.com/zaki-yama/webpack-google-apps-script-template) Template for developing Google Apps Script with Webpack

### Shims and polyfills

- [cEs6Shim. Using Es6 with Apps Script](http://ramblings.mcpher.com/Home/excelquirks/gassnips/es6shim)

[goto top ⇑](#google-apps-script-list)

## Libraries & Modules

### Using databases

- [FirebaseApp](https://github.com/RomainVialard/FirebaseApp) The Google Apps Script binding for the Firebase Realtime Database
- [oshliaer/alasqlgs](https://github.com/oshliaer/alasqlgs) AlaSQLGS is a library that enables the use of the AlaSQL.js library in Google Apps Script

### ORM (O/RM and O/R mapping tool)

- [Goodel](https://github.com/7imon7ays/Goodel) An ORM for Google Apps scripts
- [gs-spreadsheet-manager](https://github.com/jsoma/gs-spreadsheet-manager) A slightly more object-oriented, ORM-y, and altogether pleasant way of dealing with Google Spreadsheets when using Google Apps Script
- [Sheetfu](https://github.com/socialpoint-labs/sheetfu) An ORM to treat spreadsheet as database tables using Google Apps Scripts. 
- [itmammoth/Tamotsu](https://github.com/itmammoth/Tamotsu) Object-Spreadsheet Mapping for Google Apps Script

### Utility

- [gas-underscore](https://github.com/simula-innovation/gas-underscore) Underscore for Google Apps Script
- [lodashgs](https://github.com/oshliaer/lodashgs) Lodash for Google Apps Script is a library that enables the use of the lodash.js library in Google Apps Script
- [brucemcpherson/cUseful](https://github.com/brucemcpherson/cUseful) Various dependency free useful functions
- [Gexpress](https://github.com/coderofsalvation/Gexpress) Express-ish middleware for google appscript (build NODEJS-ish  applications)

### Parsing

- [Apps-Script-htmlparser2-library](https://github.com/Spencer-Easton/Apps-Script-htmlparser2-library) A browserified version of fb55/htmlparser2 modified to work in Google Apps Script
- [cheeriogs](https://github.com/asciian/cheeriogs) HTML manipulation library with jQuery-like interface.

### oAuth

- [apps-script-oauth2](https://github.com/googlesamples/apps-script-oauth2) An OAuth2 library for Google Apps Script
- [brucemcpherson/cGoa](https://github.com/brucemcpherson/cGoa) OAuth2 for Apps Script in a few lines of code

### Images & Pictures

- [ImgApp](https://github.com/tanaikech/ImgApp) This is a library of image tools for Google Apps Script

[goto top ⇑](#google-apps-script-list)

## Open Source Add-ons

- [google-docs-add-on](https://github.com/Automattic/google-docs-add-on) Publish to WordPress from Google Docs
- [email-studio-gmail-addon](https://github.com/labnol/email-studio-gmail-addon) Gmail add-on for Mail Merge and Email Scheduler
- [erickoledadevrel/crop-sheet](https://github.com/erickoledadevrel/crop-sheet) An add-on for Google Sheets that allows you to easily remove extra rows and columns

[goto top ⇑](#google-apps-script-list)

## Testing

- [gast](https://github.com/zixia/gast) Google Apps Script TAP Testing-framework
- [GSUnit](https://sites.google.com/site/scriptsexamples/custom-methods/gsunit) is a Google Apps Script based testing framework based on JUnit by Kent Beck and JSUnit by Edward Hieatt. It will allow one to run tests while developing
- [classroomtechtools/modularLibraries.gs/UnitTesting](https://github.com/classroomtechtools/modularLibraries.gs/tree/master/UnitTesting) 
Assertion and unit testing of modular libraries
- [simula-innovation/qunit](https://github.com/simula-innovation/qunit) An easy-to-use JavaScript Unit Testing framework

[goto top ⇑](#google-apps-script-list)

## Logging

- [gasl](https://github.com/zixia/gasl) Google Apps Script Logging-framework

[goto top ⇑](#google-apps-script-list)

## Snippets and assorted

### Snippets

#### Lists & collections

- [Google Apps Script Cheat Sheet](https://github.com/jychri/google-apps-script-cheat-sheet)

#### Spreadsheets

- [[Apps Script] Getting the unmerged ranges within a range](https://gist.github.com/erickoledadevrel/6fa9b256f41b5d7646ba6ed37e0f8018)
- [Google Apps Script to fill in a Document template with Spreadsheet data](https://gist.github.com/mhawksey/1170597)

#### XML

- [A function to convert an XML string to a JSON object in Apps Script, using logic similar to the sunset method Xml.parse()](https://gist.github.com/erickoledadevrel/6b1e9e2796e3c21f669f)

### Assorted

- [GoogleSheets](https://github.com/Max-Makhrov/GoogleSheets) best code I've tested in Google Sheets
- [google-apps-script-snippets](https://github.com/oshliaer/google-apps-script-snippets) Google Apps Script Snippets
- [google-docs](https://github.com/fastfedora/google-docs) Libraries and functions used within Google Docs
- [youtube/api-samples/apps-script](https://github.com/youtube/api-samples/tree/master/apps-script/snippets) The youtube-data-api.gs file in this directory contains code snippets that are generated by the Data API code snippet tool at: https://developers.google.com/youtube/v3/code_samples/code_snippets
- [google/google-apps-script-samples](https://github.com/google/google-apps-script-samples) Various sample code and projects for the Google Apps Script platform
- [googlesamples/apps-script-templates](https://github.com/googlesamples/apps-script-templates) This repository contains a number of code templates for Google Apps Script that provide example frameworks for Apps Script projects
- [derekantrican/Google-Apps-Script-Library](https://github.com/derekantrican/Google-Apps-Script-Library) A variety of functions/programs written for Google Apps Script and Google services
- [stardotbmp/google-sheet-functions](https://github.com/stardotbmp/google-sheet-functions) A single repository for open sharing of custom functions I have found to be useful generally.
- [googlesamples/apps-script](https://github.com/googlesamples/apps-script) Sample code for Google Apps Script, a cloud-based scripting service for Google Apps
- [An Example of using an HTML form (e.g: "Contact Us" on a website) to send Email without a Backend Server (using a Google Script)](https://github.com/dwyl/html-form-send-email-via-google-script-without-server)

[goto top ⇑](#google-apps-script-list)