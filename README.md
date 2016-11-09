# playvideo
Bash script to utilize youtube-dl in accord to my own needs

This script retrieves URL from given user input or clipboard or primary
(selection), attempts to extract a video, plays it and then asks the
user whether to save it to drive or not.

When this script is not being executed via terminal, a simple GUI dialog
will be made available for end-users.

Programs used are:
* mplayer
* wget (to pipe content from https to mplayer)
* yad
* youtube-dl
* xclip
* zenity
