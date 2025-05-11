# Automator Workflows For Exporting PDF Pages To JPEGs

Three (minor) variations on an Automator Workflow:

## (1) automator-workflow

Unzip, open in Automator, and run. Asks user to select a PDF file, then exports every page as a JPEG and puts them onto the desktop.

## (2) drag-and-drop-onto-app

Same as the above, but saved as a application. Drag and drop your PDF onto it to process.

## (3) print-plugin

Slightly different to (1) and (2). A print plug in for your `PDF Services` directory.

On my Mac, this is:

<img width="202" alt="Screenshot 2025-05-11 at 14 03 29" src="https://github.com/user-attachments/assets/2d476731-85a8-4d14-b6fa-25f2a58d9dff" />

(`~/Library/PDF Services`)

This adds the workflow to your `PDF` popup menu in the standard Apple `Print` dialog.

This has the advantage of letting you to specify the page range that will be exported (whereas versions 1 and 2 simply do all the pages in the file).

<img width="743" alt="Screenshot 2025-05-11 at 14 08 09" src="https://github.com/user-attachments/assets/0d23028e-747a-4385-b7b4-9f0b140094a9" />

<img width="217" alt="Screenshot 2025-05-11 at 14 08 23" src="https://github.com/user-attachments/assets/cc682c9e-8ead-4ee9-9f02-f36706c9353f" />

