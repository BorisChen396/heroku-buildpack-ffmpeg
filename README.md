# heroku-ffmpeg-buildpack

A FFmpeg buildpack for Heroku.

**⚠️ Warning: As this buildpack clones the FFmpeg source code and builds it everytime you build the app, using this buildpack will make the build time much longer!**

## How to use

Simply add this repository to your Heroku app's buildpack list, then rebuild the app to install FFmpeg.
