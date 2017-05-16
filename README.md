# 360-Degree-Stereoscopic-Video-Player
Sample 360-Degree-Stereoscopic-Video-Player for Google Daydream


This is a 360 degree player for stereoscopic videos for Google Daydream.
There is a sample stereoscopic video in Streaming Assets for reference.
You might not be able to view the video playing in the editor but should play fine on the device builds.
Checked supported formats: .mp4, .webm
Checked unsupported formats: .mov
Formats performance is due to the GVR SDK limitations.

Unity Version Used: Unity 5.6.0f3
Google VR SDK Version Used: GVR 1.3

To play videos, add files to the Streaming Assets in Assets folder.


Credits: This player was build with reference to this document - http://www.sdkboy.com/2017/01/playing-videos-daydream-vr/

In case of trouble try deleting the given GVR Assets and Plugins and import it again.
Also find GVRBackwardsCompatibility package and GVRVideoPlayer package in the assets once you import the GVR sdk in you Unity player and import them by double clicking on them as well.
