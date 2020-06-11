# google-drive-ops
This repository is intended to build common file operations I need to interact with Google Drive that is not available via their UI. 

## State of the project
At this point, I've created this repository to begin recording my thoughts on the need.

## Motivation
I have found the Google Drive UI to be lacking common file operations I need in how I am using the service, including:
- Easy file list export
- Summarization of file sizes
- Text-based file listing
- Counting files in directories (without needing to "select all") and subdirectories

## List of operations
This is a (not yet comprehensive) list of specific operations I would like to have built out.

Given a directory location:
- List all files in the directory
- Count number of folders and files in the directory
- Sum the total size of all items in the directory

## Helpful references
These are references I find helpful while researching how to build these file operations:

Description | Link
--- | ---
🐍 The official Python client library for Google's discovery based APIs | https://github.com/googleapis/google-api-python-client
Google Drive API Python wrapper library | https://github.com/gsuitedevs/PyDrive
Google Drive API v3 Reference | https://developers.google.com/drive/api/v3/reference
Drive API Instance Methods | http://googleapis.github.io/google-api-python-client/docs/dyn/drive_v3.html
