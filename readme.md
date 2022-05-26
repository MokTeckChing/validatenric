# Validate NRIC
Hello! 

This is a project to write and publish a python script to check if a Singaporean NRIC number is valid. 

The Singaporean National Registration Identity Card (NRIC) is document issued in Singapore to citizens and PRs for the purpose of identification.

As explained very well by <a href="https://ivantay2003.medium.com/creation-of-singapore-identity-number-nric-24fc3b446145">Ivan Tay</a> in his article, the last letter of the NRIC functions as a checksum to validate the NRIC number. 

<b>Please note that this does not mean that the NRIC number is in use.</b>

I am aware that several sites (including Ivan's) already function as an NRIC number validator, however i cannot a find a package that does the same thing for python.

With that in mind, the purpose of this project is twofold:
1) Practice publishing a small package to the <a href="https://pypi.org/">Python Package Index (PyPI)</a>.
2) Practice publishing an app of sorts to google cloud <WIP>
  
Do note that this project is in no way supported by the Singapore government or any legal body in Singapore.
  
This is done for fun.

The package has one method, ".validate()", that takes a non-case-sensitive input as a string and outputs either "valid", "invalid, wrong checksum",or "invalid, wrong format".