# auto-XML-reader-and-SQL-generator

This code is write in python 2.7 and urllib2 used depends on the version

The purpose of this code is for interviewing.
So there is no exceptional handler and no pattern check for inputs.

Also if you try to input url, sometimes you may input '{some url}' instead of {some url}
Eg: using 'https://uwaterloo.ca/' instead of https://uwaterloo.ca/
This problem is from my configuration in Pycharm on MAC.
The "response = urllib2.urlopen(url)" works a little bit differently
