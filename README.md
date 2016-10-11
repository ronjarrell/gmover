# gmover
Google Groups Archive Mover

The core of the code is from one of the examples of the
Google Admin-SDK Groups Migration API developer page, and the examples
of the mailbox python module.

The gluing and tweaking is by Ron Jarrell, Manager for Ecommunications
Services at Virgina Tech.  You can contact him at jarrell@vt.edu.
If this helps you, feel free to drop a line, or send a postcard :)

Creates a Google Admin-SDK Groups Migration API service object and
inserts all mail in an mbox into a group.

Note, this was written to solve a problem.  Migrating a listserv, which
generates archives that are very mbox like, and can be made an mbox with
a simple edit, to google groups.  The archives turned out to not uniformly
have message-id's, which is bad.

If it didn't write for some reason, like a bad message, we really
didn't care.  So there's a lot of cleanup that can be done.  Code
contributions accepted.  I'm posting this brute-force solution because
I didn't see any other examples out there that weren't "pay us to do it for
you," and if you're looking at this, you're probably like me, and capable
of taking this thing and tweaking it to what you need and never needing
it again.  Note this is also the first python I've done from scratch that
didn't involve the words hello and world.


