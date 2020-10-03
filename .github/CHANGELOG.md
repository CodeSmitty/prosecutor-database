# Changelog
Maintained by [@billimarie](https://www.github.com/billimarie).

## 0.3.2

### New
- Issue thread for Hacktoberfest: [HACKTOBER: Add District Attorney Data](https://github.com/billimarie/prosecutor-database/issues/80)
- Default generic article thumbnail

### Updates
- Recently Updated section into limited table view

## 0.3.1

### New
- Issue thread for contributing data: [ONGOING: District & State Attorney Data](https://github.com/billimarie/prosecutor-database/issues/80)

### Updates
- Separated README & DOCS

### Removes
- Deleted `app` & `csv-json-data`

## 0.3.0

### New
- Swapped out mLab for MongoDB Atlas

### Updates
- Synced GitHub + Heroku (`app` branch)

---

## 0.2.1
### New
- Swapped out Bootstrap 3 for Bootstrap 4 (CSS, JS)
- Returned to Meteor.js app
- Separated the app from manual data collection

### Updates
- Heroku deployment (production)
- mLab integration (MongoDB)
- Fixed annoying jump on filtering system

## 0.2.0
### New
- Reverted repo back to original Meteor.js app

### Updates
- Updated ancient NPM, Meteor packages
- Changed from MIT license to GNU GPLv3
- Separated `GraphQL` into its own branch

---

## 0.1.2
### Updates
- .csv and .json data

## 0.1.1
### New
- Created new GitHub Pages site: [USPD Guide](https://billimarie.github.io/prosecutor-database)

### Updates
- Detailed instructions for contributors who are not programmers

### Removes
- Original Light Pollution GitHub Pages site (see: handlebars.js)

## 0.1.0
### New
- Created new data collection repo

### Updates
- Detailed introduction and instructions (README.md)
- package.json
- package-lock.json

### Removes
- Wiped entire app structure

---

## 0.1.2
### Updates
- .csv and .json data

## 0.1.1
### New
- Created new GitHub Pages site: [USPD Guide](https://billimarie.github.io/prosecutor-database)

### Updates
- Detailed instructions for contributors who are not programmers

### Removes
- Original Light Pollution GitHub Pages site (see: handlebars.js)

## 0.1.0
### New
- Created new data collection repo

### Updates
- Detailed introduction and instructions (README.md)
- package.json
- package-lock.json

### Removes
- Wiped entire app structure

## 0.0.10
### New
- Mailing list section on (`home`)

### Removes
- Public images folder (moved to CDN)

## 0.0.9
### New
- Creates section for Recent Articles (`attorneyView`)
- Creates section for Recently Updated Attorneys (`home`)

### Updates
- JSON structure (`articles`)

### Removes
- Updated date on home hero

## 0.0.8
### New
- Creates Contributor page
- Creates Glossary page

### Updates
- Fixes broken route (`attorneyView`, `currentAttorney`)
- Copy editing for About page
- Updates vote ribbon link
- Updates municipal, county, and/or city attorney data fetch

### Removes
- Navbar glyphicons (replaced with Font Awesome)

## 0.0.7
### New
- Adds additional attorneys (Kim Foxx, Larry Krasner)
- Adds Elections collection
- Creates public folder (images)
- New text search functionality

### Updates
- Updates footer links
- Imports headshots
- Templates folder for housing templates
- Rebuilds main layout (search and filters, attorney list)

### Removes
- Comments out Legal History, Election sections
- Deletes retrieval limit

## 0.0.6
### New
- Adds links to social media, website, Wikipedia, Google news
- Renders relevant Cases

### Updates
- Bootstrap mark-up for basic data

## 0.0.5
### New
- Routes: individual attorney pages (yay!)
- Template folders: attorney-views, experiments, pages, sections

### Updates
- Fleshes out README.md
- Meteor release and various packages
- Template partials
- Helpers (needs work)

### Gone
- Header/Jumbotron mistake

## 0.0.4
### Updates
- README.md "Acknowledgements" section
- Renamed the repo ("light pollution" => "U.S. Prosecutor Database" / "prosecutor-database")

## 0.0.3
### New
- Rebuilt with Meteor.js
- Fixed CSS3 ribbon for election updates
- Bootstrap hack for filtering types of prosecutors

### Updates
- JSON data has been inserted into MongoDB
- Converted Handlebars to Spacebars

### Gone
- Removed prosecutor list nav from header
- No need for Gulp

## 0.0.2
Originally, prosecutor data was housed in a [.JSON masterlist](https://github.com/billimarie/light-pollution/blob/master/public/data/prosecutors.json). I pulled information from there with Handlebars. The agile prototype ran on a simple, clean, and user-friendly GitHub Pages website: [Light Pollution](https://billimarie.github.io/light-pollution).
