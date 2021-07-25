# Notice

This only works for [**Google Drive for Desktop**](https://support.google.com/drive/answer/7329379) users, NOT Backup and Sync users.

Backup and Sync users should use the original work by [**luke.digital**](http://luke.digital/adding-google-drive-to-the-explorer-sidebar/)

# Adding Google Drive for Desktop to the Windows Explorer sidebar

For those of you who use OneDrive or Dropbox you may have noticed that they create non-removable shortcuts in the Explorer sidebar. If you are also a Google Drive user you&#39;ll notice that Google Drive doesn&#39;t create the same shortcuts.

![Image of first print](http://luke.digital/content/images/2016/08/google-drive-before.jpg)

Following the steps below you can create the same shortcut for Google Drive.

**Disclaimer: This was only tested on Windows 11 Professional, Windows 10 Professional and Windows 8.1 Professional. Ensure you backup your registry before making any changes.**

## Installation

- Download this repository.
- Open  **GoogleDrive.reg**  in your favourite text editor.
- When making edits below, you must use "\\\" instead of "\\"
- Update any references of @="C:\\\Program Files\\\Google\\\Drive File Stream\\\49.0.9.0\\\GoogleDriveFS.exe,0" to wherever you've installed Google Drive, keeping ,0 at the end of the drive path
- Update any references "TargetFolderPath"="G:\\\My Drive" to wherever you have configured Google Drive to store files
- Save all changes
- Double-click  **GoogleDrive.reg**  to install and ensure you click yes when prompted.

## Results

![Image of first print](https://i.imgur.com/O6IT6J8.png)


You should now see Google Drive pinned to the Explorer sidebar.

## Credits
Original work by [**luke.digital**](http://luke.digital/adding-google-drive-to-the-explorer-sidebar/)

Google Drive for Desktop update by [**Stratium**](https://github.com/Stratium/)
