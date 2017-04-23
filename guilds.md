#### Test plan for Guilds:

- Do NOT consume any reputation packages

### Plan A: User A have no guild (Users A)
- Search for guild (success / fail), Details ok?
- User A searches for guild to join, User B destroy that guild, User A clicks Join
- Join guild with own rep less than minimum required (Must now allow join)
- Join guild with own rep higher than required (Must work)
- Join destroyd guild (Must not allow)
- Join request accepted: You must receive a notification, You must be added to the chat room

### Plan B: User B in a guild as leader (Users B, C, D)
- Check guild info, all fine?
- Search for guilds and try to join (Must not work)
- Ask user C, D to join guild
- Accept join request of user C
- Reject join request of user D
- Ask user D to join guild again
- Accept user D join request (Accepted user must be added to list, and to guild chat)
- Is user C colead and user D a regular member?
- Kick user D (Must be removed from list and guild chat), Ask the user to check if he is still in guild chat, ask to try **plan A**
- Kick user C (Must be removed from list and guild chat), Ask the user to check if he is still in guild chat, ask to try **plan A**
- Ask user C to delete the secure file, is it deleted?
- Ask user D to join, accept user D, is user D a colead ? does he have secure file?
- Ask user C to join, does he have secure file? (shouldnt)
- Check guild bank, add cash to bank, ask member C and colead D to add cash to bank. check guild bank again. all fine?
- Kick user C (B and D only in guild left)
- Decrypt your file and give guild IP to user C (unless IP already available)

### Plan C: User C as a guild leader VS user B (Users A, C)
- User A and C consume enough reputation packages to destroy guild of user B (to increase bot attack power when infecting yourself with bots)
- Ask user B and D for their IPs, hack them to check their miners cools down, are miners kep hot?

### Plan D: Buy and sell bandwidth
- Configure your guild to sell bandwidth
- Buy bandwidth from another guild (check numbers on both guilds , bandwidth used/max bandwith / available for rental ..)
- Check you sold bandwidth
- After 24 hours, did the rented bandwidth expire?
- After 24 hours guild bandwidth returned to normal?

### Plan E: Destroy a guild (X) that sold bandwidth to another guild (Y) using guild (Z)
- Did the guild (Y) IP address appear in the clients/staff file of guild (X) after destruction (must be yes)
- Did players that attacked the guild (and all the members of their guilds in (Z)) get HC for destroying (X) (1000 HC + total bank of guild (X)) ? - must be yes
