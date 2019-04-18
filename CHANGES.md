**Changes to the Palantir version:**
- WEC-Authentication channel renamed to WEC-Authentication-Other, contains subscriptions:
  - wef-subscriptions / Explicit-Credentials
  - wef-subscriptions / NTLM
  - wef-subscriptions / Account-Lockout 
- wef-subscriptions / Kerberos subscription moved to WEC7-Kerberos channel
- wef-subscriptions / Authentication subscription moved to WEC7-Authentication
- windows-event-channels / CustomEvetnChannels.man changed accordingly
- deployment folder added for scripts
- winlogbeat folder added as a potential shipping solution to ELK