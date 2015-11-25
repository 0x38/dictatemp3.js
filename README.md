dictatemp3.js
==========

__dictatemp3.js__ is a small Javascript library for browser-based real-time speech recognition.
It uses [recordermp3.js](https://github.com/kdavis-mozilla/recordermp3.js) for audio capture,
and a WebSocket connection to the
[Kaldi DNN GStreamer server](https://github.com/alumae/kaldi-gstreamer-server) for speech recognition.

API
---

The API is modelled after [Android's SpeechRecognizer](http://developer.android.com/reference/android/speech/SpeechRecognizer.html).
See the source code of [lib/dictate.js](lib/dictate.js).

Browser support
---------------

Known to work in
  - Google Chrome 41.0 on Ubuntu desktop
  - Google Chrome 45.0 on Android 5.1
  - Firefox 37.0.1 on Ubuntu desktop (unstable: often seems to lose connection to microphone)
  - Firefox 41.0 on Android 5.1 (unstable: often seems to lose connection to microphone)

See also
--------

- [Kõnele](https://github.com/Kaljurand/K6nele) contains an Android front-end to the Kaldi GStreamer server
