todo
----


OpenBSD `calendar` and `cal` subproject for simple calendar management, fancy UI, and written in `/bin/sh`.


It will show the current month `cal` and highlight the todays date. It will also show the number of unread emails is a **maildir** directory, **note: you will need to edit the MAILDIR vars at the top of the script**


`todo` also provides 3 levels of marking important events. I use them for minor, important, and critical. I suppose, you could also use them as personal, work, school.


Examples
========


Add event


    todo 01/16
    #
    # Opens the users default EDITOR
    # Saves it to calander file
    #


Add **marked** event


    todo 10/04
    #
    # In editor entry
    # Use `++ `  notice the [[:space:]] before and after the mark
    #


Add **flagged** event


    todo 02/13
    #
    # In editor entry
    # Use `:: `  notice the [[:space:]] before and after the flag
    #


Add **critical** event


    todo 02/22/2016
    #
    # In editor entry
    # Use `>> `  notice the [[:space:]] before and after the cirt
    #



Show agenda and `cal` calendar


    todo


