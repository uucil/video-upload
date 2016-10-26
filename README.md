# video-upload

TODO:

- write script
    - get track info via:
    
        lsdvd -Oy /dev/sr0
         
    - rip and transcode using mplayer: http://www.tuxradar.com/answers/707

        mplayer dvd://1 -dvd-device /dev/sr0 -dumpstream -dumpfile firsttrack.mpg

    - upload using API:
      https://developers.google.com/youtube/v3/guides/uploading_a_video

