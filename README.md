## Authoring Spatial Media for the Youtube

[Theta Ricoh](https://theta360.com/en/) is cheap and easy to use but images are soft (especially distant objects.  The camera shoots 1920x960, square pixels, 29.97fps, 44.1khz audio.  Video needs to be re-encoded into a spherical video using [their special software](https://theta360.com/en/support/download/).

Adobe Premiere seems best for cutting due to flexibility in sequence settings and such.  Reaper is the best DAW for serious sound editing.

[Here](https://support.google.com/jump/answer/6399746?hl=en&ref_topic=6399824) is Google's documentation on spatial audio.

To use spatial audio, Youtube will want audio encoded in the Ambix format, which is different from the Furse-Malham B-format many ambisonic plug-ins generate.  [Here](http://www.matthiaskronlachner.com/?p=2015) is a nice ambisonics plug-in toolkit that can convert to Ambix and offers many other features.

In premiere export the Quicktime as per [these specs](https://support.google.com/jump/answer/6400185?hl=en).
The resulting video will need metadata injected, use [this](https://github.com/google/spatial-media/releases).

Spatial audio in youtube works for Chrome on desktops and Android.  iOS just gets stereo.
