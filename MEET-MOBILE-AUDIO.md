# Google Meet mobile/tablet audio guidance

The Listening player now uses an inline HTML audio element with eager preload, media-session playback support, and an explicit loading-error message. These changes improve mobile browser playback and media controls, but **cannot guarantee audio transmission through Google Meet**.

## How to share
1. Join Meet using its Android/iOS app and unmute your microphone.
2. Check Meet microphone permission and system-wide microphone access.
3. Start screen sharing and enable **Share audio** if the device/Meet version offers it.
4. Open the PTE site and tap Play yourself (mobile browsers block autoplay without a gesture).
5. Test with a second participant. If microphone works before sharing but not after, troubleshoot Meet/device permissions.

## Platform limitations
- Browsers cannot force Google Meet to capture microphone or device audio.
- Some Android/iOS devices and Meet versions cannot share internal audio.
- Background playback may be suspended by the OS when switching applications.
- Test on the target hardware; no live device/Meet test was performed here.
