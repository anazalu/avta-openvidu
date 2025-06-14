## Description
Test case to:
- record an openVidu call with three users sharing video 
- collect video, audio and network trace

## What needs to be installed:
- testray
- sox
- wireshark (with ChmodBPF)
- ffmpeg

## Before the test:
- add a .mjpeg file to simulate screen sharing (you can make any screen recording and then use the command below)
```
ffmpeg -i input.mov output.mjpeg
```

## To run the test (better use Terminal):
```
testray execute openViduCall
```
