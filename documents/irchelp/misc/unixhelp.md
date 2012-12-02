# UNIX help page

* * *

The basic Unix commands are easy to use and work much like the basic DOS
commands. This means that rather than pointing and clicking to do things, you
type in what you want to do by name instead. On-line help is always available
simply by typing this command at your prompt: man

More on man later, let's get started!

    
    
    **(NOTE: Unix is *ALWAYS* case-sensitive!!!)**  (i.e. R vs r)  
    
    Command     What The Command Does (And syntax example if neccesary)
    ls          shows the contents of the current directory
    pwd         shows the name of the current directory
    cd          changes current directory (cd newdirectoryname)
    cd ..	    changes current directory to the parent directory
    cp          copies a file to a new filename (cp thisfile thatfile)
    mv	        renames a file (mv oldfilename newfilename)
                also moves a file (mv filename newfiledirectory)
    rm          deletes a file (rm filename)
    rmdir       deletes a directory (rmdir directoryname)
    mkdir       makes a new directory (mkdir directoryname)
    cat         shows the contents of a file (cat filename)
    more        shows the file contents a page at a time (more filename)
    less        see above but allows scroll back also (less filename)
    head        shows the first few lines of a file (head filename)
    tail        shows the last few lines of a file (tail filename)
    pico        starts a friendly but limited file editor program
    vi          starts an unfriendly but powerful file editor program
    date        even you can figure this one out 
    time        see above
    w           shows who is logged in and what they are doing
    finger      user info check (finger user -or- finger user@host)
    pine        starts a friendly e-mail program
    mail        starts an unfriendly e-mail program
    tin         starts a friendly UseNet News reader program
    nn          starts an unfriendly UseNet News reader program
    login       starts the login procedure
    passwd      starts the new password change program
    logout      now what do you think this command might do? Hmmm?
    talk        starts a 2-way chat (talk user -or- talk user@host)
    jobs        shows the # of jobs you have running
    kill        kills a job (kill %N)  -> where N is that job number <-
    ctrl-Z      stops the current program
    fg          resumes that program
    ctrl-C      cancels the current program (try quit or exit first)
    lynx        starts a friendly text-based World Wide Web browser program
    cal         shows a calender for any month and year (cal MM YYYY)
    ctrl-L      re-draws the screen in case it gets messed up somehow
    ping        verifies that an address exists (ping address.name.here)
    
    

To get more help on any of the commands, do this: **man command_name_here**.
For example, to see all the different ways to use flags and wildcards with the
ls command, do this: **man ls**. In fact, you should do this, for all of the
above commands before use. And for more info on the manual itself do this:
**man man**

That about covers all the basics, get a book for the intermediate and advanced
stuff, you won't regret it! Here are two general reminders... Always make a
back-up file before you try to transfer, edit or rename any really important
files. Never do what someone else tells you to do unless you can determine
what the command will do or you really trust the person.

* * *

![-navigational bar-](/irchelp/Pix/ihnavbar.gif)

[ [go back](/irchelp/) | [search](/irchelp/search_engine.cgi) |
[help](/irchelp/help.html) | [send email](/irchelp/mail.cgi) ]

[all pages (C) IRCHELP.ORG or original authors](/irchelp/credit.html)
