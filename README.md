# heroku-ffmpeg-buildpack

A FFmpeg buildpack for Heroku.

**⚠️ Warning: As this buildpack builds the FFmpeg source code when the app is built, using this buildpack will make the app's build time much longer!**

## How to use

Simply add this repository to your Heroku app's buildpack list, then rebuild the app to install FFmpeg.
