---
layout: post
title: 'Bytes to sound to bytes'
---

Experiments in translating a bytestream into audio and back, play it over speakers, record it with a microphone and decode it to bytes again.

Experiments where made using Paul Austers voice reading a book aloud.

255 samples of his reading (2 second duration per sample) where chosen and a script takes a bytestream piped into it (for example a bitmap) and starts speaking the bytestream aloud using the Paul Auster samples as a representation of the bytes

Another script listens to the sound, looks for audio fingerprints and looks them up to get the associated byte value. It then outputs a bytestream to stdout and another script reconstructs in this case a bitmap from the bytestream.

The transmission of data is lossy but the fun of listening to it live with Paul Austers voice is making up for it.


{% include image.html url="https://www.youtube.com/watch?v=cjQir99ix00" image="projects/bytes_to_sound_to_bytes/thumb.jpg" %}

Watch the video [here](https://www.youtube.com/watch?v=cjQir99ix00).

Get the code [here](https://github.com/sloev/bytes-to-sound-to-bytes)
