# Marklevy.net v6 (Vuefinder)

### Premise

A Vue-based Headless Wordpress site
 - Primarily a 3d Printing blog
 - Also a portfolio site

## Globals
- Background Images, light and dark mode galleries. Seperate by month.
	- Lack of a month defaults to previous month.
	- Background image loads from a random roll by a gallery
		- Will display optional detail info if the image entry contains it.
		- Cookie is set to load same image on reload in event that Gallery has more than one. Expires after 6 hours.

 - New Background image per section.

## Site Map

### Home

 - Loading Phase: Structure Online, Presentation Online, Behaviors Online, All Systems Nominal
	* Cookie is set in the aftermath to prevent re-running of intro loading animation. Expires after 7 days

### About

 - Profile Picture Gallery header:
	- Framed shot of standing desk
	- Linkedin Photo?
	- Casual Photo?


	"I'm Mark, I build websites"

 - Skills
 	- Front End
 		- HTML
 		- CSS
 			- SASS
		- Javascript
			- Typescript
		- MVC Frameworks
			- React
			- Vue
		- Frameworks
			- D3
			- GSAP
			- Three.js
	- Back End
		- PHP
		- SQL
		- Python
		- Content Management Systems
			- Wordpress
			- Drupal
	- Build Tools
		- Node.js
		- npm scripts
		- Docker
			- Lando
		- Git
	- Development Tools
		- Github
		- Bitbucket
		- Pantheon
		- Azure
		- Acquia
	- Concepts
		- Performance Optimization
		- WCAG Accessibility
		- 508 Compliance
	- Design
		- Adobe Creative Suite
		- Figma
		- Maya

 - Career

 - Not sure if I want to do this actually

 - Social
 	- Instagram
 	- Blue Sky
 	- LinkedIn

 [Next Link: Portfolio]
 	- Not sure if button? Scroll? Both?


### Portfolio

 - TODO: Refer to document on laptop for latest projects. Consolidate with portfolio doc.
 - Kinda like my original project interface. Maybe repurpose that for one or two case studies?

[Next Link: Contact]

### Contact

 - Postcard
 	- Custom PHP Mailer
 	- Custom Spam Honeypot
 	- Send confirmation stamps postcard, flips over and sends. Photo is Google(?) location photo Title text of "Greetings from {{ location }}"

### Printer Blog

  - Homepage:
  	HERO: Minimal?
  	TOP: Curated Feature. 1 or tile of 3. Can be anything from the feed, including an external link.
  	BLOG: Latest Posts with Sidebar. Latest 5, link to listing.
  	PRINTS: Latest Prints, Sidebar continues. Latest 5, link to listing.
  	VISUALIZATION: Two random(ish) visual charts with full link to the data page
  	SPECS: Two Column Content Area, Printers Details Card/Material Details Card. Link to both feeds
  	SIDEBAR: Search Bar, Link to all feeds, Resource Links

 ### Printer Feed Details

 #### Prints

  - Fields:
  	- Printer
  		- Selectable Printer from Printer Content Type
  			- JS Populates the following:
  				- Post Number
  				- Brand
  				- Model
  				- Nozzle Type
  				- Nozzle Size
  				- Print Bed
  				- Build ID Number
	- Material
		- Up to Five Materials selectable from Material Content Type
			- JS Populates the following:
				- Post ID Number
				- Type
				- Manufacturer
				- Color
				- Nozzle Temperature
				- Bed Temperature(If Primary Material)
				* Not sure if the first material should be primary, or if that should be selectable?

	- Model
		- Type of Model Select Field. Downloaded model selected by default.
			- Download Link appears when selected
		- Modification of Download
			- Software Checkboxes
			- Download Link is optional
		- Custom
			- Software Checkboxes
			- File Download(Optional)

	- Prints
		- Print Instances
		- Bed Cleanliness
			- Rubbing Alcohol
			- Dish Soap
			- Windex
		- Adhesive
			- Tape
			- Gluestick
		- Print Time
			- Start
			- End
		- Results
			- Success
				- Notes(Optional)
				- Print Grade
					- A: Flawless
					- B: Imperfections
					- C: Not Sellable
					- D: Poor Quality
			- Fail
			- Aborted
				- Notes(Mandatory)
				- Error Type
					- Bed Adhesion
					- Calibration Error
					- Clogged Extruder
					- Extruder Blob
					- Filament Jam
					- Layer Shift
					- Out of Filament
					- Overheating
					- Spaghetti Monster
		- Overrides(Optional)
			- Toggle
			- Selector for:
				- Hotend Temp
				- Bed Temp
				- Temp Change Point(Percentage)
			- Print Speed Selector
				- Speed(Percentage)
				- Change Point(Percentage)

	- Photos
		- Photo Gallery. (Look into Imgur hosting or similar)

#### Printer

 - Re-use what's on current site, but make field repeatable.
 	- Each new version requires all fields re-entered.
 		- Update script to auto-populate with previous entries if possible.
 		- This will allow tracking of updated printer versions.

#### Material

 - Re-use what's on current site.


#### Projects

Might need to write a draft project in order to determine what visual assets I would need.


