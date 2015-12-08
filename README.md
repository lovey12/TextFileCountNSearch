# TextFileCountNSearch

*************************************************************************************************************************************************************************************************************************
Important Points to consider for running this application
---------------------------------------------------------------------------------------------------------------
1). Only text (.txt) files are valid. This validation is taken care of in the application.

2). As per the definition of a sentence, in this application is considered(simple sentence) to end with a period(. followed by whitespace) or question mark.(?)


for example- 

   a) The happy birthday machine    -> This is not a sentence.
   b) The happy birthday machine.   -> This is a sentence. 
   c) The happy birthday machine?   -> This is a sentence.  



3). There is a driver class - (TestMain)- which needs filename as an input parameter to the method "readInputFile(String fileName)" and a pattern to search for as an input to the method "searchPattern(String pattern)".

4). The special characters(NonAlphaNumeric character) are not part of any word. They are just counted as an individual characters.

5). A custom Exception class is created to throw fileName invalidations.

6). The result count shows-

  a) Total number of sentences.
  b) Total number of words. (Includes duplicate words)
  c) Number of Distinct words.
  d) Number of characters.(Including special characters)

**************************************************************************************************************************************************************************************************************************

