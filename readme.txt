Acknowledgements



1) shellcheck Exception:

If the information is intended for the user and not 
for processing (ls -l ~/dir | nl; echo "Ok to delete these files?") 
you can ignore this error (SC2012) with a directive.

2) 'current' shell history

I have taken 'current' shell to be simply the user's login shell as
would be identified by the methods discussed in the following thread:
 http://stackoverflow.com/questions/3327013/how-to-determine-the-current-shell-im-working-on
The history of commands for the subshell in which the script is running (which could also be identified as being the 'current' shell), is, after invoking the bash 'history' built-in - always empty.
