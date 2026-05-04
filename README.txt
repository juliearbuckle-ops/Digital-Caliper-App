CALLIPER READER
===============
A phone-based tool for recording digital calliper measurements directly into
Google Sheets. Point your camera at the calliper display, and the app reads
the number and logs it to the right cell automatically. Dropdown fields for
material, integrity, colour and cortex % are voice-activated too.

Built for lithic analysis fieldwork - no typing, no transcription errors.


WHAT YOU NEED
-------------
- An Anthropic API key (console.anthropic.com) - costs pennies per session
- A Google account with access to the spreadsheet
- Chrome on Android, or Safari on iOS


FIRST TIME SETUP
----------------
1. Open the app at https://juliearbuckle-ops.github.io/Digital-Caliper-App
2. Enter your Anthropic API key and tap CONTINUE
3. Tap SIGN IN (top right) and log in with your Google account
4. The app finds the first empty row in column C automatically


RECORDING A SPECIMEN
--------------------
The app steps through fields in order:
  Height - Width - Mes Thickness - Prox Thickness - Dist Thickness - Weight
  then: Material - Integrity - Colour Patina - Colour Raw Mat - Cortex %

For camera fields (measurements):
  - Hold the phone over the calliper display
  - Keep the number inside the green guide box
  - Tap CAPTURE - the reading is logged and the app moves to the next field

For dropdown fields:
  - Tap the option from the list, or say its name (e.g. "flint", "proximal")

When a row is complete, tap NEXT ROW to move on.


VOICE COMMANDS
--------------
Turn on with the VOICE button. Say:

  "capture"       - read the calliper display
  "skip"          - leave this field blank and move on
  "next"          - go to the next row
  "row 4"         - jump to a specific row number
  "[option name]" - select a dropdown option (e.g. "dark grey", "distal")


TIPS
----
- Good lighting makes a big difference for the camera reading
- Fill the green guide box with the display for best results
- If a reading looks wrong, tap the dot for that field to go back and recapture
- Column B (Unique ID) is filled in manually in the sheet - the app skips it
- The session log at the bottom confirms every cell written


JUMPING TO A SPECIFIC ROW
--------------------------
Type a row number in the JUMP TO ROW box and tap GO.
Or say "row [number]" with voice on.
