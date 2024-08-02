# Destination Pet Site Template

This is the site template for Destination Pet websites.

<img src="previews/DPSiteTemplate.png?raw=true" alt="Standard DP website preview" width="50%">

## Structure

* `files`: Folder with the UI kit XD file and possibly other files.
* `previews`: Folder with screenshots of the site template.
* `site`: Content package of the content that will be copied for each site created from this template (templates, pages, etc.).
* `theme`: Sources of the template theme to modify how the site looks (CSS, JS, etc.).

## Steps to generate the site template:

## Prerequisites
1. Install Maven (to be able to use the packaging script).
2. Install Node.js

## Update template scripts

* Replace the below folders with the updated contents
1. /conf/dp-site-template
2. /content/dam/dp-site-template
3. /content/dp-site-template
4. /content/experience-fragments/dp-site-template

Note: DO NOT modify anything except only the above folders.


## Build locally

Note: Below commands to be executed at the template root:

1. Initialize the project:

   ```bash
   npm install
   ```

3. Build the site template:

   ```bash
   npm run build
   ```

The site template ZIP file is now located below the template root: `dp-site-template-{version}.zip`.
