# GoogleDriveEmbedderWithFilePreview
A tool to easily embed google drive folder within websites, with the ability to navigate into subfolders and preview pdf, sheets, doc etc file types without making the user leave your website. Works on any webpage: Wordpress, Wix, Google Sites etc 

I have created a tool to embed any Google Drive folder (publicly viewable) on any webpage. It has the ability to let the user navigate into subfolder, preview pdf/xls/doc etc files without making your visitor leave your webpage. The file preview opens in a modal window.
All you have to do is get an API key from Google Developer Console and get the folder id.


Embed the following code:

<iframe src="https://googledriveembedder.collegefam.com/?key=YOUR_API_KEY>&folderid=THE_FOLDER_ID" style="border:none;" width="100%"></iframe>

It works using an iframe and the website which is being embedded is guaranteed to be live forever (it runs on Google servers).

# To get an API Key
1.) Go to https://console.developers.google.com/ 
Create a new project or choose any existing project.

2.) From the menu button, go to 'APIs and Services' --> 'Dashboard'. Then click on 'Enable APIs and Services'.

3.) In the top search bar, type 'Google Drive API'.
A new page will open. Click on the button to enable the drive API. Then go to "credentials' tab, and create credentials.

Don't add any restrictions if you aren't sure how restrictions work. The API key works fine without any restrictions and there is low chance of your API key being misused, since google provides the drive api for free, and it is practically unlimited (1 billion requests per day, and can be increased even more, if the first billion requests were genuine.)

# Common Mistakes
Make sure that the folder you are sharing is publicly viewable to anyone with the link. This is done in the sharing settings.

If the folder you are sharing is actually a shortcut (Google has recently removed the option 'Add to My Drive' and replaced it with 'Add shortcut to drive') then it won't work properly. The shortcuts to files inside another folder will also not work.
To solve this, you can download the folder, upload to your own Google Drive and then share the folder id.




If you are facing any problems, contact me at studyforexams ( at ) gmail
