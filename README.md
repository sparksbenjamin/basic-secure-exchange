# base-secure-exchange
This is a collection of scripts that will create some basic security rules on your Office 365 Exchange online.  You will need to update the scripts to use your EMAIL and PASSWORD!  Once you have done that they script should run and create or update the rules on exchange.  Each script is explaned below. 

Unverified Sender - This rule wll add [Unverified Sender] to the subject of inbound emails that have not passed the SPF check.  This will alert the mailbox user that the email may not be who it claims to be from.  Simple google search will show and explain what that means and how to proceed. This is a common prefix to put in the subject line and is in common practice to enclue GMAIL, YAHOO and AOL.
  
  
