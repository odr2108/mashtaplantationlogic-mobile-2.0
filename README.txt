MASHTA PLANTATION LOGIC — MOBILE IMAGE INDEX
============================================

This is an independent companion website, not a modification of the original
Mashta Plantation Logic HTML. The source project remains untouched.

CONTENTS
- index.html                Mobile exhibition / index interface
- data.js                   90 event records + 48 estate asset records
- media/events/             Optimized detail images of historical events
- media/assets/             Optimized detail images of estate assets
- media/thumbs/             Small, lazy-loaded index thumbnails

RUN LOCALLY
Open index.html on your computer while all files remain in their folders.
The index will work without a server because data.js is a normal JS file.

MAKE IT ACCESSIBLE BY QR CODE
1. Put the complete contents of this folder onto a PUBLIC HTTPS site.
   For example, deploy the folder to Netlify Drop or to GitHub Pages.
   (You cannot use a QR code pointing to your computer's file:/// address.)
2. Copy the public address of the deployed index.html page, e.g.:
   https://your-example-site.netlify.app/
3. Generate a QR code for that public URL and print or display it.
4. Test the QR code using a phone that is NOT connected to your computer.

DIRECT LINKS TO INDIVIDUAL RECORDS
Append a hash to the public URL to open a specific record, e.g.:
  https://your-example-site.netlify.app/#PI010
  https://your-example-site.netlify.app/#worker-cottages

The "Share ID" button inside any record copies such a link for direct access.

EDITING
The dataset lives in data.js (window.MASHTA_DATA). Each record has its own:
 id, title, date, category, description, imageNote, image, thumbnail,
 relatedEvents and relatedAssets.
Editing data.js does not change the original desktop constellation or estate map.

SCOPE AND PROVENANCE
Descriptions for events use interpretive arguments from the legacy 100-event
catalog, matched by exact title to the 90 retained event IDs. Event images,
image notes, dates and linked IDs follow the latest project package. The 48
asset images come from its estate photo index; asset descriptions come from
ASSET_DESCRIPTIONS.js where present.

Asset-to-event links are a curated navigation layer based on named topics,
not assertions that an image proves a particular historical event. Items
without established dates show "Date not specified"; six unlocated items
have no descriptive text in the source and are marked accordingly.

Last source package used:
MashtaPlantationLogic_ForensicPresentation_QuieterShutter_v7.zip
22 November 2026
