# Google Apps Script List

<!-- toc -->

* [Resources](#resources)
  * [Useful sites & blogs](#useful-sites--blogs)
  * [Awesome code & things](#awesome-code--things)
  * [Lists](#lists)
* [Development](#development)
  * [Starter Kits](#starter-kits)
  * [Shims and polyfills](#shims-and-polyfills)
* [Libraries & Modules](#libraries--modules)
  * [Using databases](#using-databases)
  * [ORM (O/RM and O/R mapping tool)](#orm-orm-and-or-mapping-tool)
  * [Utility](#utility)
  * [Parsing](#parsing)
  * [oAuth](#oauth)
  * [Images & Pictures](#images--pictures)
  * [Data Studio community connectors](#data-studio-community-connectors)
  * [Pack modules and universal libraries](#pack-modules-and-universal-libraries)
* [Open Source Apps & Add-ons](#open-source-apps--add-ons)
* [Chatbots](#chatbots)
* [Testing](#testing)
* [Logging](#logging)
* [Snippets and assorted](#snippets-and-assorted)
  * [Snippets](#snippets)
    * [Lists & collections](#lists--collections)
    * [Spreadsheets](#spreadsheets)
    * [Gmail](#gmail)
    * [XML](#xml)
    * [JSON](#json)
  * [Assorted](#assorted)

<!-- tocstop -->

## Resources

* [Google Apps Script Community](https://groups.google.com/forum/#!forum/google-apps-script-community) Google Groups
* Search by label [[google-apps-script]](https://github.com/search?q=topic%3Agoogle-apps-script) on GitHub
* SO [[google-apps-script]](http://stackoverflow.com/questions/tagged/google-apps-script) tag
* Google Apps Script communities collection [#85](https://github.com/contributorpw/google-apps-script-awesome-list/issues/85)

### Useful sites & blogs

* [Digital Inspiration](https://www.labnol.org/topic/google-apps-script) Amit Agarwal's site
* [mashe.hawksey.info](https://mashe.hawksey.info/category/google/google-apps-script) Martin Hawksey's site
* [ramblings.mcpher.com](http://ramblings.mcpher.com/) Desktop Liberation - the definitive resource for Google Apps Script and Microsoft Office automation
* [googleappscripting.com](http://googleappscripting.com) Google Apps Script Tutorials and Examples • Making Google Apps Script Accessible to Everybody
* [scriptsexamples](https://sites.google.com/site/scriptsexamples/custom-methods) A set of code samples and libraries to foster programming in Google AppsScript to be easy
* [tanaikech.github.io](https://tanaikech.github.io/tags/google-apps-script/) The `Google Apps Script` tag of the Kanshi's blog
* [andrewroberts.net](http://www.andrewroberts.net) The Andrew Roberts's site
* [kutil.org](http://www.kutil.org/search/label/google%20apps%20script) The `google apps script` tag of Ivan Kutil's blog
* [googleappsscript.org](http://www.googleappsscript.org/) Google Apps Script Tutorial
* [scriptingwithshiva.blogspot.com](https://scriptingwithshiva.blogspot.com/) Scripting With Shiva It will help those wants to start Google Apps script Development from scratch
* [benlcollins.com](https://www.benlcollins.com/) Ben Collins's site
* [pulse.appsscript.info](https://pulse.appsscript.info/) User contributed tutorials and news
* [yagisanatode.com](https://yagisanatode.com/) Section in Yagi's blog about `Google Apps Script`, including tutorials and templates
* [script.gs](https://script.gs/) Discussions, tutorials and tips about Google Apps Script and related technologies

### Awesome code & things

* [Making a virtual machine in Google Sheets](http://briansteffens.com/2017/07/03/google-sheets-virtual-machine.html) Register of Apps Script consultants
* [Easy data scraping with Google Apps Script in 5 minutes](http://www.kutil.org/2016/01/easy-data-scrapping-with-google-apps.html)
* [Send SMS with Google Sheets and your Android Phone)(https://www.labnol.org/send-sms-google-sheets-200402)

### Lists

* [Apps Script consultants](https://docs.google.com/presentation/d/1U1y6Vjf5ClEof15JLw4qg7tpjpo4MHk7uhVKpjVkA9M/edit?usp=sharing)
* [Learning Google Apps Script](https://gist.github.com/labnol/0b67f812a827fd9babc5) The best resources for learning Google Apps Script, the glue that connects GSuite services including Gmail, Google Drive, Calendar, Maps, Analytics and more

[goto top ⇑](#google-apps-script-list)

## Development

* [google/clasp](https://github.com/google/clasp) Develop Apps Script projects locally using clasp (Command Line Apps Script Projects) CLI
* [gas-local](https://github.com/mzagorny/gas-local) Execute and test your google app scripts locally in node.js
* [gamified_journal](https://github.com/brainysmurf/gamified_journal) Proof of concept of a local development / push toolchain for Google Apps Scripting
* [gas-github](https://github.com/leonhartX/gas-github) Chrome-extension to manage Google Apps Script(GAS) code with github/github enterprise
* [ggsrun](https://github.com/tanaikech/ggsrun) This is a CLI tool to execute Google Apps Script (GAS) on a terminal
* [gdrive](https://github.com/prasmussen/gdrive) Google Drive CLI Client
* [MaartenDesnouck/google-apps-script](https://github.com/MaartenDesnouck/google-apps-script) gas, for locally developing Google Apps Script projects
* [gas-lib](https://www.npmjs.com/package/gas-lib) NPM package to add code auto-completion for Google AppsScript in your preferred code editor
* [AppsScriptColor](https://chrome.google.com/webstore/detail/appsscript-color/ciggahcpieccaejjdpkllokejakhkome) _(3 700+ users)_ This Chrome extension provide 2 dark color themes for the google apps script editor. It also allows to use folders to sort your files more cleanly
* [KaiShoya/autocomplete-gas](https://github.com/KaiShoya/autocomplete-gas) Google Apps Script auto completion for [Atom editor](https://atom.io/packages/autocomplete-gas)
* [rudimusmaximus/DevFlow](https://github.com/rudimusmaximus/DevFlow) A Dev Flow for Google Apps Script
* [fossamagna/gas-webpack-plugin](https://github.com/fossamagna/gas-webpack-plugin) Webpack plugin for Google Apps Script
* [Andrew Roberts' Dev Flow](https://docs.google.com/document/d/1GgTZmY4VFzejVl7cTeKOc7PWtyZnhu-fFhysZ2ShRN4/edit#heading=h.v2f4oyhmg3cs) - Description of a dev flow using Github assistant.
* [Set up a Local Development Environment for Apps Script](https://www.youtube.com/watch?v=KxdCIbeO4Uk) - Write code faster inside VS Code.
* [maelcaldas/clasp-types](https://github.com/maelcaldas/clasp-types) A d.ts generator for clasp projects
* [namaggarwal/clasp-token-action](https://github.com/namaggarwal/clasp-token-action) Github actions for clasp for CI for your AppScript projects.

### Starter Kits

* [apps-script-starter](https://github.com/labnol/apps-script-starter) A starter kit for building Google Apps Script projects with modern JavaScript ES6, Webpack, Babel and ESLint inside Visual Studio Code
* [realworld-apps-script](https://github.com/lastlink/realworld-apps-script) JWT REST API following the RealWorld API spec
* [gas-minimal-boilerplate](https://github.com/asciian/gas-minimal-boilerplate) A minimal boilerplate with webpack for Google Apps Script
* [google-apps-script-template](https://github.com/nirazul/google-apps-script-template) A feature rich task runner for Google Apps Script to write, lint and push modern code to your documents
* [gas-shell](https://github.com/JeanRemiDelteil/gas-shell) Starter template to develop locally Google AppsScript project with your preferred code editor (include build and publish as Add-on commands)
* [artnc/gas-es6-webpack](https://github.com/artnc/gas-es6-webpack) ES6+Webpack boilerplate for Google Apps Script
* [google-app-script-ts-jest](https://github.com/lastlink/google-app-script-ts-jest) Rest api in typescript with jest unit tests working with vscode debugger
* [howdy39/gas-clasp-starter](https://github.com/howdy39/gas-clasp-starter) A starter template for Google Apps Script by clasp
* [zaki-yama/webpack-google-apps-script-template](https://github.com/zaki-yama/webpack-google-apps-script-template) Template for developing Google Apps Script with Webpack
* [JeanRemiDelteil/gas-starter-kit](https://github.com/JeanRemiDelteil/gas-starter-kit) Empty project to start develop in Google AppsScript locally
* [faresd/google-apps-script_travis-ci](https://github.com/faresd/google-apps-script_travis-ci) Automating Apps Script build, test, deployment and publishing in Chrome Webstore as an add-on using Travis CI
* [sao-clasp](https://github.com/takanakahiko/sao-clasp) With one command, Generate a Google Apps Script project that uses clasp
* [gazf/google-apps-script-ci-starter](https://github.com/gazf/google-apps-script-ci-starter) Google Apps Script with CI/CD(wercker) Starter Kit

### Shims and polyfills

* [cEs6Shim. Using Es6 with Apps Script](http://ramblings.mcpher.com/Home/excelquirks/gassnips/es6shim)

[goto top ⇑](#google-apps-script-list)

## Libraries & Modules

* [Google Apps Script Library Database](https://github.com/tanaikech/Google-Apps-Script-Library-Database) Directory with more than 200 libraries

### Using databases

* [FirebaseApp](https://github.com/RomainVialard/FirebaseApp) The Google Apps Script binding for the Firebase Realtime Database
* [oshliaer/alasqlgs](https://github.com/oshliaer/alasqlgs) AlaSQLGS is a library that enables the use of the AlaSQL.js library in Google Apps Script

### ORM (O/RM and O/R mapping tool)

* [Goodel](https://github.com/7imon7ays/Goodel) An ORM for Google Apps scripts
* [gs-spreadsheet-manager](https://github.com/jsoma/gs-spreadsheet-manager) A slightly more object-oriented, ORM-y, and altogether pleasant way of dealing with Google Spreadsheets when using Google Apps Script
* [Sheetfu](https://github.com/socialpoint-labs/sheetfu) An ORM to treat spreadsheet as database tables using Google Apps Scripts. [Sheetfu's Python version](https://github.com/socialpoint-labs/sheetfu)
* [itmammoth/Tamotsu](https://github.com/itmammoth/Tamotsu) Object-Spreadsheet Mapping for Google Apps Script
* [Gexpress-middleware-RESTsheet](https://github.com/coderofsalvation/Gexpress-middleware-RESTsheet) Spreadsheet exposed as http REST endpoints (based on tamotsu)
 *[GoogleScriptSQL](https://github.com/YionoFr/GoogleScriptSQL) How to transform Google Sheet and Google App script into a SQL Database

### Utility

* [gas-underscore](https://github.com/simula-innovation/gas-underscore) Underscore for Google Apps Script
* [lodashgs](https://github.com/oshliaer/lodashgs) Lodash for Google Apps Script is a library that enables the use of the lodash.js library in Google Apps Script
* [brucemcpherson/cUseful](https://github.com/brucemcpherson/cUseful) Various dependency free useful functions
* [Gexpress](https://github.com/coderofsalvation/Gexpress) Express-ish middleware for google appscript (build NODEJS-ish applications)
* [tanaikech/RangeListApp](https://github.com/tanaikech/RangeListApp) RangeListApp is a GAS library for retrieving, putting and replacing values for Spreadsheet by a range list with a1Notation using Google Apps Script (GAS)
* [syslogic/google-apps-script](https://github.com/syslogic/google-apps-script) CloudDatastore.gs is a client for Google Cloud Datastore, which runs as a Service Account
* [Sheetbase](https://sheetbase.dev) Build REST API server, websites and apps using Google Apps Script.
* [UrlShortener](https://github.com/mhawksey/UrlShortener) A replacement for the Google Apps Script UrlShortener advanced service that uses bit.ly
* [michalliu/google-app-script-jsonrpc](https://github.com/michalliu/google-app-script-jsonrpc) An implementation of JSON-RPC 2.0 specification
* [johndturn/google-apps-script-storageservice](https://github.com/johndturn/google-apps-script-storageservice) Utility class (built in TypeScript) for storing small or large values in Google Apps Script properties
* [GetEditType](https://github.com/tanaikech/GetEditType) Library for retrieving the edit types of the OnEdit event trigger of Spreadsheet using Google Apps Script
* [zlib.js for Google Apps Script](https://github.com/takumab21/zlib.js) Compact zlib, deflate, inflate, zip library in Google Apps Script

### Parsing

* [Apps-Script-htmlparser2-library](https://github.com/Spencer-Easton/Apps-Script-htmlparser2-library) A browserified version of fb55/htmlparser2 modified to work in Google Apps Script
* [cheeriogs](https://github.com/asciian/cheeriogs) HTML manipulation library with jQuery-like interface

### oAuth

* [apps-script-oauth1](https://github.com/gsuitedevs/apps-script-oauth1) An OAuth1 library for Google Apps Script
* [apps-script-oauth2](https://github.com/gsuitedevs/apps-script-oauth2) An OAuth2 library for Google Apps Script
* [brucemcpherson/cGoa](https://github.com/brucemcpherson/cGoa) OAuth2 for Apps Script in a few lines of code

### Images & Pictures

* [ImgApp](https://github.com/tanaikech/ImgApp) This is a library of image tools for Google Apps Script
* [GPhotosApp](https://github.com/sudtanj/gas-GPhotosApp) This is a Google Photos REST API library for Google Apps scripts
* [InstagramApp](https://github.com/sudtanj/gas-InstagramApp) Instagram images API for Google Apps scripts to download images and video

### Data Studio community connectors

* [googledatastudio/community-connectors](https://github.com/googledatastudio/community-connectors) This repository contains open source content for Google Data Studio

### Pack modules and universal libraries

* [classroomtechtools/modularLibraries](https://github.com/classroomtechtools/modularLibraries.gs) A collection of importable, modular libraries for any GAS project

[goto top ⇑](#google-apps-script-list)

## Open Source Apps & Add-ons

* [google-docs-add-on](https://github.com/Automattic/google-docs-add-on) Publish to WordPress from Google Docs
* [email-studio-gmail-addon](https://github.com/labnol/email-studio-gmail-addon) Gmail add-on for Mail Merge and Email Scheduler
* [erickoledadevrel/crop-sheet](https://github.com/erickoledadevrel/crop-sheet) An add-on for Google Sheets that allows you to easily remove extra rows and columns
* [ericyd/gdrive-transfer](https://github.com/ericyd/gdrive-transfer) Web app to transfer ownership of a Google Drive folder, including all sub-folders and documents
* [ericyd/gdrive-copy](https://github.com/ericyd/gdrive-copy) Google Drive Copy Folder
* [stardotbmp/slack-gas-signup](https://github.com/stardotbmp/slack-gas-signup) Google Apps Script Html Webapp as sign-up page for a slack channel
* [Atlassian Cloud for Gmail add-on](https://bitbucket.org/atlassian/atlassian-cloud-for-gmail) An add-on to view information about items from Jira Cloud & Bitbucket Cloud, and take action on them from Gmail.
* [Davepar/gcalendarsync](https://github.com/Davepar/gcalendarsync) Apps Script for syncing a Google Spreadsheet with Google Calendar
* [Google Forms](https://github.com/labnol/google-forms) Google Scripts for sending emails, generating PDFs and setting response limits inside Google Forms.
* [Website Monitor](https://github.com/labnol/website-monitor) Apps Script for monitoring the uptime of websites inside Google Sheets.
* [Gmail Unsubscriber](https://github.com/labnol/unsubscribe-gmail) Google Script for unsubscribing from emails newsletters and other bulk email in Gmail with one click.
* [Flubaroo](https://github.com/edcodeorg/flubaroo) Add-on for Google Spreadsheets that allows teachers to quickly grade assignments, get insights into student performance, and share grades with their students electronically
* [Code Blocks](https://github.com/alexwforsythe/code-blocks) Syntax highlighting for Google Docs

[goto top ⇑](#google-apps-script-list)

## Chatbots

* [Google Apps Script Sheet MQ](https://github.com/scrthq/GoogleAppsScriptSheetMQ) Google Apps Script endpoint for Hangouts Chat bot using Sheets as a message queue
* [Facebook-bot-Google-Apps-Script](https://github.com/JZL/Facebook-bot-Google-Apps-Script) A Facebook messenger bot implemented in Google Apps Script
* [GroupMe Bots with Google Apps Script](https://github.com/william-reed/GroupMe-Bots-With-Google-Apps-Script) Examples and resources for using the GroupMe Bot API with Google Apps Script

## Testing

* [gast](https://github.com/zixia/gast) Google Apps Script TAP Testing-framework
* [GSUnit](https://sites.google.com/site/scriptsexamples/custom-methods/gsunit) is a Google Apps Script based testing framework based on JUnit by Kent Beck and JSUnit by Edward Hieatt. It will allow one to run tests while developing
* [classroomtechtools/modularLibraries.gs/UnitTesting](https://github.com/classroomtechtools/modularLibraries.gs/tree/master/UnitTesting) Assertion and unit testing of modular libraries
* [simula-innovation/qunit](https://github.com/simula-innovation/qunit) An easy-to-use JavaScript Unit Testing framework

[goto top ⇑](#google-apps-script-list)

## Logging

* [gasl](https://github.com/zixia/gasl) Google Apps Script Logging-framework
* [BetterLog](https://github.com/peterherrmann/BetterLog) Logging library that extends the native apps script Logger, mainly to allow logging to a GSheet
* [BBLog](https://github.com/andrewroberts/BBLog) Logging library that further extends BLog to give logging to a Firebase DB multiple logging instances logging of function names and line numbers log the user's email address or ID, in a full or disguised format automatically format log GSheet

[goto top ⇑](#google-apps-script-list)

## Benchmarking

* [Benchmark](https://gist.github.com/tanaikech/848aeafaac1ec676900bb78e3ce220b6) Benchmark: Loop for Array Processing using Google Apps Script without V8

## Snippets and assorted

### Snippets

#### Lists & collections

* [Google Apps Script Cheat Sheet](https://github.com/jychri/google-apps-script-cheat-sheet)
* [Andrew Roberts' Scripts and Snippets](http://www.andrewroberts.net/scripts-and-snippets/)
* [google-apps-script-snippets](https://github.com/oshliaer/google-apps-script-snippets) Google Apps Script Snippets
* [google/google-apps-script-samples](https://github.com/google/google-apps-script-samples) Various sample code and projects for the Google Apps Script platform
* [googlesamples/apps-script-templates](https://github.com/googlesamples/apps-script-templates) This repository contains a number of code templates for Google Apps Script that provide example frameworks for Apps Script projects

#### Spreadsheets

* [[Apps Script] Getting the unmerged ranges within a range](https://gist.github.com/erickoledadevrel/6fa9b256f41b5d7646ba6ed37e0f8018)
* [Google Apps Script to fill in a Document template with Spreadsheet data](https://gist.github.com/mhawksey/1170597)
* [ReshapeReshaping functions for Google Spreadsheets](https://github.com/rgertenbach/Reshape)
* [Sample HTML/JS to parse a Google Spreadsheet](https://gist.github.com/terrywbrady/a03b25fe42959b304b1e)
* [Example on how to export a Google sheet to various formats, includes most PDF options](https://gist.github.com/Spencer-Easton/78f9867a691e549c9c70)

#### Gmail

* [Apps-Script-Gmail-Push-Notifications-v2](https://github.com/Spencer-Easton/Apps-Script-Gmail-Push-Notifications-v2) Register a Gmail account for push notifications and programmatically set up the the proper pubsub publishing channels and subscriptions
* [Gmail2GDrive](https://github.com/ahochsteger/gmail2gdrive)  Automatically stores and sorts Gmail attachments into Google Drive folders

#### XML

* [xmlToJson](https://gist.github.com/erickoledadevrel/6b1e9e2796e3c21f669f) A function to convert an XML string to a JSON object in Apps Script, using logic similar to the sunset method Xml.parse()

#### JSON

* [JSON Puller](https://gist.github.com/jalcantarab/0eb43b13c97e4f784bd0be327f6ced52) Transforms the data of a given Spreadsheet Sheet to JSON.
* [JSONPath](https://script.google.com/a/google.com/d/1BtmcVnmTKAxqdiHN9Q5cM6M6E5MUMzVtQjSfav-OIQxNIoACkDdlst53/edit) Extract data from complex data structures with simple expressions. Google Apps Script version of [this](https://github.com/dchester/jsonpath) library.

### Assorted

* [GoogleSheets](https://github.com/Max-Makhrov/GoogleSheets) best code I've tested in Google Sheets
* [google-docs](https://github.com/fastfedora/google-docs) Libraries and functions used within Google Docs
* [youtube/api-samples/apps-script](https://github.com/youtube/api-samples/tree/master/apps-script/snippets) The youtube-data-api.gs file in this directory contains code snippets that are generated by the Data API code snippet tool at: https://developers.google.com/youtube/v3/code_samples/code_snippets
* [derekantrican/Google-Apps-Script-Library](https://github.com/derekantrican/Google-Apps-Script-Library) A variety of functions/programs written for Google Apps Script and Google services
* [stardotbmp/google-sheet-functions](https://github.com/stardotbmp/google-sheet-functions) A single repository for open sharing of custom functions I have found to be useful generally
* [googlesamples/apps-script](https://github.com/googlesamples/apps-script) Sample code for Google Apps Script, a cloud-based scripting service for Google Apps
* [An Example of using an HTML form (e.g: "Contact Us" on a website) to send Email without a Backend Server (using a Google Script)](https://github.com/dwyl/html-form-send-email-via-google-script-without-server)
* [rudimusmaximus/BurningGAS](https://github.com/rudimusmaximus/BurningGAS) Demonstrate various Google Apps Script using a menu of functions inside a fresh Google Sheet and container bound editor
* [GAS-Framework](https://github.com/andrewroberts/GAS-Framework) - library boilerplate that provides logging ([BBLog](https://github.com/andrewroberts/BBLog)) and error handling ([Assert](https://github.com/andrewroberts/Assert))
* [AutoSteamGifts](https://github.com/sudtanj/AutoSteamGifts) A Modified version based on Python script by joaopsys that run on Google server using Google App Script to automatically enter every giveaway that you can afford on SteamGifts.com
* [BkperApp](https://github.com/bkper/bkper-app) A simple and secure way to access the Bkper API through Google Apps Script infrastructure

[goto top ⇑](#google-apps-script-list)
