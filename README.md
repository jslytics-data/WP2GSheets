WP2GSheets
WP2GSheets is a Google Apps Script that fetches WordPress posts and inserts them into a Google Sheet. It supports custom fields, categories, tags, and author data, and includes auto-formatting options. It simplifies the process of transferring WordPress content to Google Sheets for reporting and analysis.

Usage
To use WP2GSheets, follow these steps:

Open the Google Sheet where you want to insert your WordPress posts.
Go to Tools > Script Editor.
Copy and paste the contents of wp2gsheets.gs into the editor.
Save the script and run the getWordpressPosts() function.
Grant the necessary permissions.
Check your sheet to see the WordPress posts inserted.
Customization
WP2GSheets supports custom fields, categories, tags, and author data. You can customize which fields are inserted into the sheet by modifying the fields array in wp2gsheets.gs. You can also customize the date range of posts fetched by modifying the after and before properties in the args object.

Auto-formatting
WP2GSheets includes auto-formatting options for certain fields. For example, the title field is formatted as a hyperlink to the post URL. You can customize the auto-formatting options by modifying the applyCustomFormatting() function in wp2gsheets.gs.

License
This project is licensed under the MIT License.
