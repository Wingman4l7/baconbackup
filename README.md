baconbackup
===========

### About ###
Node.js tool for archiving a Reddit user's comments.
Tested as working on Node.js v0.10.26.

### How to Install ###
This requires [Node.js] and the [restler] HTTP client library.
The former will have to be downloaded and installed.
Once that is done, the latter can be installed via this command:
    
    npm install restler 

[node.js]: http://nodejs.org/
[restler]: https://github.com/danwrong/restler

### How to Run ###
Set the `user` variable to be the handle of the person whose comments you wish to archive.  To use, navigate to the installed directory and run this command:

	node baconbackup.js
    
### Details ###

Currently baconbackup defaults to archiving as many comments as possible *(the upper limit is 1000)*.  At a maximum of 100 comments per page request and a minimum of 2 seconds between page requests, the fastest baconbackup can run through a full backup is **20 seconds**.
    
### License ###
While obviously open-source, I have yet to decide which license this should be under.  It will probably end up being under the [GPL] or some flavor of [Creative Commons].
[GPL]: http://www.gnu.org/licenses/licenses.html
[Creative Commons]: http://creativecommons.org/licenses/

### Origins & Credit Due ###

Credit goes to [AlliedEnvy] for always being ready with a clever project name.
[AlliedEnvy]: https://github.com/AlliedEnvy

### Donations ###
Like this script?  You can send Bitcoin donations to: `1F7kfMNUNQy8e52RHnQAWYXeaYfzFqHJAZ`

*Quick reference:* $1 USD is currently: <img src="http://btcticker.appspot.com/mtgox/1.00usd.png">

Alternatively, you can use [Gittip](https://www.gittip.com/Wingman4l7/).