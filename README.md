baconbackup
===========

### About ###
[Node.js] tool for archiving a Reddit user's comments as an HTML file.
[Node.js]: http://nodejs.org/
Defaults to archiving the maximum number of comments viewable via a user's profile, which is currently 1000.

Tested as working on Node.js v0.10.26.

### How to Run ###
To use, navigate to the installed directory and run this command:

    node baconbackup.js YOUR_USERNAME
	
### Speed & Options ###

At a maximum of 1000 comments available, a maximum of 100 comments per page request, and a minimum of 2 seconds between page requests, the fastest a full backup can be done is **20 seconds**.

You can optionally hard-code the `user` variable if you're going to repeatedly run baconbackup on the same user and don't want to have to keep typing their handle into the commandline.
    
### License ###
While obviously open-source, I have yet to decide which license this should be under.  It will probably end up being under the [GPL] or some flavor of [Creative Commons].
[GPL]: http://www.gnu.org/licenses/licenses.html
[Creative Commons]: http://creativecommons.org/licenses/

### Credit Due ###

Credit goes to [AlliedEnvy] for always being ready with a clever project name.
[AlliedEnvy]: https://github.com/AlliedEnvy

### Donations ###
Like this script?  You can send Bitcoin donations to: `1F7kfMNUNQy8e52RHnQAWYXeaYfzFqHJAZ`

*Quick reference:* $1 USD is currently: <img src="http://btcticker.appspot.com/mtgox/1.00usd.png">

Alternatively, you can use [Gittip](https://www.gittip.com/Wingman4l7/).