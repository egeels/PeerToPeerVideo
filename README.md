# PeerToPeerVideo

Modified index.html in the following ways:
  
  1. Added an audio field to objects on lines 41 and 42.
  2. Added a section starting on line 90 to grab the user's screen info.
  3. Added extra video elements for local and remote screen. 
  4. Added a couple lines in gotRemoteMediaStream to account for both video tracks, and also
     to account for the case when either use chooses not to share screen audio.
  5. Accounted for audio feedback by muting local videos by default on lines 81 and 94.

index.html should now function as desired.
