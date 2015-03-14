## SnakeTail 1.9.0 ##

### Feature changes ###

  * Quick jump shortcut has changed to ALT+KeyUp/KeyDown (Instead of CTRL+KeyUp/KeyDown).
  * Keyword highlight can now be just line coloring without being 'Alert Highlight'. Meaning that ALT+KeyUp/KeyDown will ignore them.(Ex. green color for success).
  * Quick jump also works for EventLog where it jumps between Warnings and Errors.
  * Added 'Copy as Path' to context menu.
  * Possible to specify multiple files when using command line.
  * Faster discovery of new files when monitoring network path for the latest file to tail.
  * Execute external tool when keyword match, with support for environment variables (Ex. play sound).
  * Toggle the tail window to be 'Always on top'.
  * Configuration window now has a 'Save as default'-button.

### Minor changes ###

  * Fixed unhandled exception when copy to clipboard fails, because other application is holding lock.
  * Fixed unhandled exception when trying to monitor an invalid file path for the latest file to tail.
  * Fixed unhandled exception when trying to monitor a file without having proper access rights.
  * Fixed unhandled exception when given invalid path to session file.
  * Fixed crash dialog so it doesn't become hidden behind main application.
  * Fixed bug where 'File Reopen Check Interval' could not get higher than 59 secs
  * Fixed unhandled exception when closing the application.
  * Less flicker when changing between different window tabs.

### Download ###

  * [SnakeTail.v1.9.0.x64.msi](https://googledrive.com/host/0B4mlaSkLLFxsVXVQaXJkTjQ4UXc/SnakeTail.v1.9.0.x64.msi)

  * [SnakeTail.v1.9.0.x86.msi](https://googledrive.com/host/0B4mlaSkLLFxsVXVQaXJkTjQ4UXc/SnakeTail.v1.9.0.x86.msi)

  * [SnakeTail\_v1.9.0.zip](https://googledrive.com/host/0B4mlaSkLLFxsVXVQaXJkTjQ4UXc/SnakeTail_v1.9.0.zip)

If wanting an older version go to [Previous Releases](DownloadsOld.md)