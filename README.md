# OVTWiki-Bot
This repo will contains logic and output created by the OpenVoice-Tech Wiki Bot.

## Phoneme list
The bot "OVTWiki-Bot-PhonemeList" is checking all pages on https://OpenVoice-Tech.net that are assigned to the category "Phoneme list" and try to figure out a language code in brackets () of the page title. It then will check if that language code is supported by eSpeak. A table on that wiki pages has at least need three columns.
* 1st column: The word in it's written form
* 2nd column: The way the word should be spoken
* 3rd column: The phoneme sequence (IPA code) (calculated by the bot if language is supported, or filled manually)

Then the bot will create a simple csv file for easy list handling and upload it to this repo in the subfolder (/phoneme-list)
