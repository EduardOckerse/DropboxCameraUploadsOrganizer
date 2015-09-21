# DropboxCameraUploadsOrganizer
Created for personal use to simplify the organizing of the sometimes huge folder of Dropbox users "Camera Uploads".

This small java applicacion will copy all the files from all the files located where the .jar file is located (subfolders included) and create a new directory tree with the following format:
YEAR/Monthname (taken from  EXIF data if available, else from filename).
If file can't be copied original will be left untouched, if copied correctly the original file will be deleted.
