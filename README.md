# chocolatey-lzip
Chocolatey Packages for lzip utility.

## What's lzip?

Lzip is a lossless data compressor. The lzip utility is a command line tool. Read all about it at the project page: [http://www.nongnu.org/lzip/](http://www.nongnu.org/lzip/)

## What are in these package files?

They are mainly here for me to keep track of the packages I submitted to chocolatey. I don't really want to maintain this on chocolatey.org (since it's not my utility) but lzip wasn't on chocolatey already, so I packaged it up real quick and submitted it. If the author wants to take over the packages that's fine with me, just contact me to let me know.

## Why did I need lzip?

Android package backups (`adb backup`) are lzip-compressed. Doesn't seem as though lzip is super common, 7-zip [won't support lzip](https://sourceforge.net/p/sevenzip/discussion/45797/thread/e23f6a3e/) (due to political reasons?), so it was bothersome. Hope this helps someone!

-Marcus
