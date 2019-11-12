# ListUsersByUPN
Powershell script to list users UPN and output to CSV if needed

At one point while troubleshooting some issues in an O365 hybrid environment we realized that the UPN for some service accounts was creating an error with the Azure AD side of things. I put together this script to audit usernames/emails vs. their respective UPNs to make sure everything matches.

Once you've exported this to CSV it becomes easier to work some excel magic to compare columns and highlight ones that don't match. In my case this resulted in moving some service accounts out of OUs where they had been improperly placed.
