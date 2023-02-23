Central Document Processing Center (autodoc)
========================================================================
Application uses latex in backend
-----------------

Front end web server, takes input for various tasks

a. chapterwise text files for the respective documents

b. view,update,bersion history options against a document

c. ssubmitting text files, view generated document, approval of the document needs to be incorporated in the workflow

d. generated documents needs to be shared with the users as per access control list

e. a user database containing user details.

f. authorization database containing level of access for the documents against the document.

g. method to provision access level and record them in authorization database.

h. a user can create documents once he is approved as an author

i. all authors need to be assigned an mandatory reviewer and approver before approval as an author

j. all approvals would have a field to contain helpdesk ticket id or an uploaded document id to ensure that approvals are in line with formal approvals.

--------------------

Back end Server needs to process all the text files for a document, and provide various options.

a. create document/chapter/figure/table options

b. update document/chapter/figure/table option

c. add/delete document/chapter/figure/table option

d. maintaining version control against all the text and pdf documents.

e. option to rollback to any existing text file or document

If required this tool may be required to be integrated with other tools such as ldap,ad,smtp,smsc,log server,splunk,zoom,jira,google meet,eventbrite

-----------------------

