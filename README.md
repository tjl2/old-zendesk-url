# old-zendesk-url
This script will generate an old-style ZD URL when given a new one, or a ticket number as an argument.

It's designed to be used with TextExpander as a shell script snippet.

## Installation
* Copy old-zendesk-url to /usr/local/bin
* Make a Shell Script TextExpander snippet with these contents:

    #! /bin/bash
    /usr/local/bin/old-zendesk-url %clipboard
* Give it the abbreviation of 'oldzd' (or whatever you prefer)
* Copy the new ZD URL, type 'oldzd'. Huzzah!
