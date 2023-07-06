## France

### Feedback sources worth monitoring
* Mozilla Community forums: https://forums.mozfr.org/search.php?search_id=newposts
* Recent tweets in French: https://twitter.com/search?q=Firefox%20lang%3Afr&src=typed_query&f=live

### Identified issues impacting users in France
* Maps on Viamichelin.com can't be printed because of Bug 976173 - preserveDrawingBuffer: false breaks printing of Canvas / WebGL - https://bugzil.la/976173
* No login autofill on Boulanger.com firefox-bug France [#12](https://github.com/pascalchevrel/firefox-per-country/issues/12)
  - Investigation in progress, bug related to the use of Shadow DOM 
* intermarche.com asks users to switch to Chrome [#118004](https://webcompat.com/issues/118004)
* impots.gouv.fr blocks Firefox mobile https://webcompat.com/issues/121515
* Dashlane extension causes performance issues to Firefox starting with version 115 https://bugzilla.mozilla.org/show_bug.cgi?id=1838448

### Solved issues
* www.leboncoin.fr - Firefox is an unsupported browser https://github.com/webcompat/web-bugs/issues/115403 bad parsing of version 110, it believes it is IE 11 -> we froze the `rv:` part of the UA to 109 as a temporary measure
* Bug 1717806 - Video does not play at tf1.fr with ETP set to STRICT - https://bugzil.la/1717806
    - Solved via remote settings

### Potential issues worth investigation
* Multiple reports on Twitter and mozfr that mycanal can't be accessed
* laposte.com invoices can't be downloaded https://twitter.com/SebuPretender/status/1595405391201984513
* UberEats not working with Nightly and ETP https://github.com/webcompat/web-bugs/issues/114611
* Ministry of Justice refuses Firefox connections: http://github.com/pascalchevrel/firefox-per-country/issues/10
