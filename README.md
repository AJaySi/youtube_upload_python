Start Here: https://developers.google.com/youtube/v3/guides/uploading_a_video
This one is good too: https://github.com/jonnekaunisto/simple-youtube-api

--------------------------------------------
Simple python3 script to upload yt videos in bulk.
The one i found on web was py2, so changed it to py3.

I will update this with features like:
1). Going through all videos, given in a folder.
2). Run in background and upload videos from given folder, as soon as made available.
Based on timestamps.

Ex:
python3 upload_video.py --file="reel.mp4" --title="Summer vacation in California" --description="Had fun surfing in Santa Cruz" --keywords="surfing,Santa Cruz" --category="22" --privacyStatus="private"
