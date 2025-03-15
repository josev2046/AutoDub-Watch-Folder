# AutoDub-Watch-Folder
Automated video dubbing and upload script using Watchdog to monitor a folder for matching MP4/MP3 file pairs, then extracting original audio, merging with external audio, and uploading the dubbed video to Vimeo.

![image](https://github.com/user-attachments/assets/c7ce8f98-f4c3-4536-875e-edddc78a34a5)


Experimental Python script designed to automate the dubbing of video files with separate audio tracks and upload them to Vimeo, as per my patterns here:

https://github.com/josev2046/Watch-Folder-Automation

https://github.com/josev2046/Media-Dubbing-Pipeline


I am using the watchdog library to monitor a designated folder for new video files (file pairs must have the same name, e.g., mydub.mp4 and mydub.mp3). When a new video is detected, the script automatically extracts the original audio, merges the video with a corresponding external audio track, and uploads the dubbed video to Vimeo.


[![DOI](https://zenodo.org/badge/932304327.svg)](https://doi.org/10.5281/zenodo.15033361)


