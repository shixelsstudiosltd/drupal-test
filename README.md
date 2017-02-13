# Skills Evaluation

# Repository
The repository to be cloned is hosted on GitHub at:
https://github.com/shixelsstudiosltd/drupal-test

# Background
Our client, Diamond Bank, is wanting to manage branch location details online. As part of the initial development, they have provided us with a CSV of four Lagos-area store addresses.
The CSV is located in the repository.
Your goal is to create a simple CRUD app to manage these resources, as well as a view of the locations on a Google Map.

# Tasks
Use your preferred local environment. When evaluating, we will be using a MAMP eniornment.
Though not a normal standard, please commit and push any work to the master branch of your repository.
Commit early and often. Keep your code clean and easy to read. Add comments where you think it makes sense. If it makes sense to write tests, please do.
Complete as many of these as possible. Please use Drupal (PHP) and MySQL for your application.
- Add CSV data to newly created branches database table
  - (Commit a seed SQL file)
- Create a homepage
  - Using data from database, display a Google Map with markers displaying the branches
    - If an API key is needed, use AIzaSyDODBvoMEvGETT7FEaReKf5cQ09aqI0jNA
  - Also display an HTML table with branches data
- Create a create page
  - Display a form to add new branch/location data to database
- Create an update page
  - Add link to branches table on homepage to update specific record
  - On update page, display a form to update existing location data in database
- Add a delete button to branches table on homepage to delete a specific record

# Nice-to-have tasks
- Add columns for created and updated timestamps to database table
  - Update code to save appropriately to said columns
- Add Bootstrap styles to markup
  - Using links to CDN works fine
- Add form validation to require all fields for create and update forms
- Add Javascript to display a "confirm alert" box when deleting a store record

# How you will be judged
We will look at code structure most importantly. We will aso look at design (UI/UX). 
