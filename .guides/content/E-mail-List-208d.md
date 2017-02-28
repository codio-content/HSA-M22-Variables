We are creating an e-mail list for our new Codio members.
We have a list of names and would like to make e-mail lists with the member's name @ codio.com
After a good start, we decided that listing the members in individual variables was not the way to go... please help us by putting the members into a single list and using the list index to print each of the member's e-mail addresses.

{Test Code}(python Variables/UserName.py)

|||guidance
# Solution
name = [ "Sophia","Jackson","Emma","Aiden","Olivia","Lucas","Ava","Liam"]  
for first in name:
   first = first+"@codio.com"
   print first
|||