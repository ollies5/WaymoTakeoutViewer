# WaymoTakeoutViewer
Requested your data from Waymo? You can use this web app to view it all in an easily digestable format.

![Screenshot of App](https://s3.us-west-000.backblazeb2.com/ollie-cdn/LDBHq26KAJQ9.jpg)

**This is a work in progress! Some things are definitely broken.**

Roadmap:
- Multi stop trips actually working
- Actual error messages so you can see what went wrong
- Automatic fixing of corrupted .zips
- A better way to seperate each trip since some are bunched together in a single .json file
- A lifetime stats page with things like total spent, longest trip etc.

This web app is designed to be easy to use - just a single file to download that's ready to go.

## Usage
1) Download `index.html` and open it up in your chosen web browser
2) Upload your archive with the takeout data (everything stays local and is processed on your device)
   **NOTE**: Waymo Takeouts tend to get sent over in a corrupted .zip. This will need to be rezipped before upload. Just extract it, zip it up again, making sure to keep the file structure the same.
4) Voila! Take a look at all your trips!
