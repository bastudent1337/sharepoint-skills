# Rename Files with Date Prefix — Demo Content

Demo content for the [rename-files-date-prefix](../) skill. Use these sample files to set up a working demo of the skill in SharePoint.

## What's included

The `sample-files/` folder contains documents with a mix of filename states to demonstrate the full range of skill behaviour:

- Files without date prefixes — will be renamed to `yyMMdd-OriginalFilename`
- A file already prefixed with a 6-digit date — will be skipped automatically

## Setup

1. Create or open a SharePoint document library.
2. Upload all files from `sample-files/` into the library.
3. Install the [rename-files-date-prefix](../) skill into your SharePoint Skills library (see the skill's README for install steps).
4. From a Copilot agent, ask: *"Prefix all files in this library with their created date."*

## What to expect

The agent will:
- Retrieve all files, including those in subfolders
- Show a preview table with current names, new names, folder paths, and status for each file
- Ask for confirmation before making any changes
- Rename files to `yyMMdd-OriginalFilename` format using each file's created date
- Skip any file whose name already starts with a 6-digit date prefix
