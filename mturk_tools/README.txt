Mechanical Turk External HIT Posting Tools
------------------------------------------

Files Included:
1) createExternalHIT.py
2) boto-2.2.2.tar.gz


How to Setup the 'boto' Python Package:
1) Go to the 'boto-2.2.2/' folder, and run 'python setup.py install'

How to Create and Post an External HIT to MTurk:
1) Fill in the paramters in 'createExternalHIT.py'
2) To post your task, run 'python createExternalHIT.py', a URL for your new task should be returned
  --> Note that this URL might not be immediately active, if it is not, give it a moment and try again

How to Delete an External HIT Posted to MTurk:
1) Get the "HIT ID" returned by 'createExternalHIT.py' (printed to command line)
2) Run 'deleteExternalHIT.py <HIT_ID_HERE>'

