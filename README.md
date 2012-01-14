# git-audio-commit

Adds two commands to git to support adding and reading audio files to commit messages.

## Installation

    gem install git-audio-commit

## Adding audio to a commit

Use `git audio-commit` instead of git commit. The audio file should be one
that is supported by `afplay`, mp3, aiff and wav should work.

    git audio-commit -m "<text message>" --audio <audio file>

## Hearing the logs

You can play back the logs using:

    git say-log

This will support the same arguments as git log.

## Requirements

Currently only works on Mac OSX since it uses the `afplay` command line utility.

## Copyright

Copyright (c) 2012 Sean Geoghegan. See LICENSE.txt for
further details.

