google-docs
===========

Libraries and functions used within Google Docs

Forked from https://github.com/fastfedora/google-docs

To use
======
- Create a new spreadsheet.
- Open the script editor.
- Copy/paste the code in Code.gs
- Save your script.
- Test with =ImportJSON(“http://date.jsontest.com", “/date”, “noInherit, noTruncate”) in your spreadsheet.

Added the following features and fixes:
- [FEATURE] ability to process paginated JSON feeds
- [FEATURE] enabled custom function, in spreadsheet mode
- [FIX] fixed missing first row on some feeds
