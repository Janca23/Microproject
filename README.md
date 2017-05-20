# Microproject
Lets get Creative :D


#Microproject “Web-site Analyzer”
Objectives
Write a command line program that analyses the structure of any given web-site. This means that \n 
starting from a given URL all links the refer to the same web-site are explored and eventually \n
written to a file holding the result of the analysis. \n
The program is started the following way: \n
./analyze[.exe] http://orf.at \n
This will cause the program to read the web-page identified by the given URL (“http://orf.at”) in \n
this case, extracting all links (of type “http” or “https”, depending on the given URL) that refer to \n
other page on the same site (all pages at “http://orf.at”). \n
While the program is working it keeps printing the currently analyzed web page: \n
READING: http://orf.at \n
READING: http://orf.at/ \n
READING: http://orf.at/#/ \n
READING: http://orf.at/#content \n
READING: http://orf.at/#ss-networkNavigation \n
READING: http://orf.at/festwochen17/ \n
READING: http://orf.at/light?redirect=http://orf.at/m/ \n
READING: http://orf.at/stories/2390719/ \n
READING: http://orf.at/stories/2391289/ \n
READING: http://orf.at/stories/2391511/2391510/ \n
READING: http://orf.at/stories/2391682/ \n
...\n
Once all pages have been found the program prints something like this:\n
There were 292 pages found on http://orf.at.\n
Additionally all web pages found are written to a file called \n
out.txt.\n
Hints:\n
Web pages are written in HTML and links to other pages (or within a page) are represented by the \n
href attribute of the anchor tag “<a>” \n

Links can have several forms:\n

They can start with different protocols (eg. http, https, mailto, tel, ..)\n

They can be relative (=they do not start with a protocol at all,  see \n
http://www.webreference.com/html/tutorial2/3.html for an explanation)\n
You need to follow all links that belong to the same web site (= that have a common base URL). Do\n
not follow any links to other web-sites!\n
Be aware that every page can have links to any other page!\n
So avoid getting trapped in circles make sure that every web page is visited only once!\n
Submission\n
You can do this project alone or in groups of two, whichever scenario you prefer. Your final version \n
needs to be uploaded to moodle.\n
Your program has to start with a comment section that includes:

Author(s)

List of all external libraries that need to get installed for the program to run
No other comments are allowed!
The submission is followed by a submission interview in which you are asked about your program 
and might be invited to perform some minor changes on the fly. This will make sure that you have 
understood what you were doing.
Deadline:  June 26th 2017, 8:00am
