# Rename Files with Date Prefix

Renames all files in a SharePoint document library — including files in subfolders — to prefix them with their created date in `yyMMdd` format (e.g., `251203-Status Report.pdf`). Always shows a preview before committing any changes.

## What you get

- All files prefixed with their created date in `yyMMdd` format (2-digit year, 2-digit month, 2-digit day)
- A preview table showing current names, new names, folder paths, and status before any changes are made
- Automatic skip for files already prefixed with a 6-digit date — no double-prefixing
- Recursive processing across all subfolders
- Graceful error handling — one failure does not stop the rest of the batch

## Demo content

Sample files for trying this skill end-to-end are in the [demo/](./demo/) subfolder. Upload them to a library before running the skill. Skip this folder when uploading the skill to SharePoint.

## Contribution

| Property | Value |
|---|---|
| Author | Leon Armston |
| GitHub | [LeonArmston](https://github.com/LeonArmston) |
| First published | May 2026 |
