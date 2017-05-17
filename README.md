#Google Webmaster Tools Bulk Url Removal Chrome Extension

##What does this extension do?
This extension allows people looking to bulk remove multiple pages showing up in the Google Index, such as a site that has changed substantially. Normally Google forces you to input these one by one through their 90 day temporary hiding tool at the Google Index > Remove URLs tool and their not so obvious URL removal tool at https://www.google.com/webmasters/tools/removals which allows you to flag pages that don't exist on the internet any more.

This extension will submit to both for you, saving lots of time and frustration


##Installation 
1.  Download the extension from [github](https://github.com/noitcudni/google-webmaster-tools-bulk-url-removal/archive/master.zip) and unzip it.
2. Go to **chrome://extensions/** and turn on Developer mode.
3. Click on **Load unpacked extension . . .** and load the extension.
4. Close all instances of Google Chrome and open it again. An alert will pop up to tell you developer mode is enabled, if it wasn't before.

##Usage
1. Create a list of urls to be removed and store them in a file. All urls are separated by \n. See [How to Extract a List of All URLs Indexed by Google for Your Website](https://www.highposition.com/blog/how-to-extract-list-urls-indexed-by-google-for-your-website/) for an easy way to get all links from a website from Google Search results.
2. Go to Google's webmaster tools.
3. Click on Google Index -> Remove URLs.
4. You should now see a new drop-down with several removal options, along with a "Choose File" button.
5. Click on the Choose File button.
6. Select the file you created in step 3.
7. The screen will cycle through the URLs from the file in order. If you need to stop it, hit ESC.
8. If you run into the error "You have exceeded your quota limit!", (seems to be ~90 in one go with a cooldown of about 15 minutes in between, and a 500 URLs per weekas of 17th May 2017), go into https://www.google.com/webmasters/tools/removals, see which the last file submitted is (at top), and go into your text file and you can the rows above your last submission.
9. Save this file as a new file, allow for the cooldown to occur, and then continue once you're quota has refreshed.
