# WP2GSheets
*This is a Google Apps Script (GAS) library for fetching WordPress posts, pages, tags, categories, and users, and saving them to Google Sheets.* 

## Getting Started


Usage
To use WP2GSheets, follow these steps:
1. Create a new Google Sheet by clicking on File > New > Google Sheets.
2. Open the script editor by clicking on Tools > Script Editor, or create a new project from https://script.google.com/home
3. Create new scripts for each file in the repo, and copy/paste the code
4. Replace the siteDomain, spreadsheetId, and any other variables in each script
4. Save the script by clicking on Save.
5. In the script editor, click on the getAllWordPressData Script and hit Run

Auto-formatting
WP2GSheets includes auto-formatting options for certain fields. For example, the title field is formatted as a hyperlink to the post URL. You can customize the auto-formatting options by modifying the applyCustomFormatting() function in wp2gsheets.gs.

License
This project is licensed under the MIT License.
