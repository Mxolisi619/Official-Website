IAMLEGEND WEBSITE TEMPLATE

WHAT'S INCLUDED
- index.html: your editable website
- media/photos/: put photos and cover art here
- media/music/: put MP3 tracks here
- media/videos/: put MP4 music videos here

HOW TO PREVIEW
1. Extract the ZIP file.
2. Open index.html in Chrome, Edge, Safari or Firefox.
3. The sample media will not play/show until you add files with the matching names or change the CONFIG section.

HOW TO CUSTOMISE
1. Open index.html in a code editor (VS Code is a good option).
2. Search for "const CONFIG" near the bottom.
3. Change the artist bio, email, social links, and music/video/photo lists.
4. Add your actual media files to the matching media folders.
5. Save and refresh index.html.

MUSIC
Add MP3 files to media/music and set the file path, for example:
{ title: "New Song", description: "Single · 2026", file: "media/music/new-song.mp3" }

VIDEOS
For uploaded MP4 files:
{ title: "New Video", description: "Official video", youtube: "", file: "media/videos/new-video.mp4" }
For YouTube, use its embed URL:
{ title: "New Video", description: "Official video", youtube: "https://www.youtube.com/embed/VIDEO_ID", file: "" }

PHOTOS
Add JPG, PNG or WebP files to media/photos and include their paths in CONFIG.photos.

SOCIAL LINKS
Replace the sample URLs with the exact URLs to your artist profiles. Delete any social entry you don't use.

IMPORTANT LIMITATION
This is a static HTML website. It lets visitors play/view the media you publish, but it does not create a secure upload dashboard and cannot save files uploaded by visitors. To add material to a live website, upload the files using your hosting provider's file manager and update the CONFIG section, or later connect a content management system (CMS) for dashboard-style publishing. Video files can be large, so hosting them on YouTube and embedding them can be easier.
