# heroku-ffmpeg-buildpack

A FFmpeg buildpack for Heroku.

*Warning: As this buildpack directly clone the FFmpeg source code and build it, using this buildpack will make the build time much longer!*

## How to use

Simply add this repository to your Heroku app's buildpack list, then rebuild the app to install FFmpeg.
