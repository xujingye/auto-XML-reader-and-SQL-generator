# auto-XML-reader-and-SQL-generator

This code is written in python 2.7 and urllib2 used depends on the version

The purpose of this code is for interviewing.
So there is no exceptional handler and no pattern check for inputs.

Also if you try to input url, sometimes you may input '{some url}' instead of {some url}
Eg: using 'https://uwaterloo.ca/' instead of https://uwaterloo.ca/

Eg: calling xmlReaderAndSqlGenerator("meta",["content", "http-equiv"], "({@0},{@1},{@2})", "INSERT INTO TABLE1 COL1 COL2 COL3", 'https://uwaterloo.ca') will return all information of meta class with attributes of content and http-equiv and then generate INSERT SQL statement





