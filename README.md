# j4x-api-collection
An attempt to help the Joomla! 4 early adopters mainly focused for developers. It's an unofficial Postman collection of official Joomla 4.0.x API

[Joomla! 4 Webservices API Documentation](https://documenter.getpostman.com/view/7443864/UVRDF5KV "Joomla! 4 Webservices API Documentation")


## Installation
- Download the latest version of j4x-api-complete-collection.postman_collection.json from the file list above
- Open Postman
- Click on Import
- Click on Upload Files to browse for the JSON file you just downloaded
- You should now have a new collection of endpoints in Postman
- Click on the collection, then on the ... on the right of the collection to open the settings for the collection
- Set your own values for Authentication and Variables per the steps below
- Test a generic GET request from the list to then confirm your authentication is working and your base_path is set correctly.

## Authentication
Authentication is done using a Joomla API Token. To get the token, go to your Super User profile in your Joomla 4 Installation and activate then copy the API key. In Postman, edit the Collection and then click on the Authorization tab.
- Select Type = "API Key"
- For the Key field, enter "X-Joomla-Token"
- In the Value field, paste your Joomla API Token
- For the Add To field, leave the value as "Header"
- Click Update to save the settings or click on Variables tab to modify your Base Path variable.

## URLs
The URLs are set via *base_path*.  You should set this variable within your collection.
- Click the 3 dots on the collection.
- Select Edit.
- Click on the variables tab.
- Add (or update) the *base_path* variable, setting the Initial Value field to the URL for your Joomla for installation.

## Documentation
The Postman generated Api documentation of Joomla! 4 Webservices collection
[Joomla! 4 Webservices API Documentation](https://documenter.getpostman.com/view/7443864/UVRDF5KV "Joomla! 4 Webservices API Documentation")
