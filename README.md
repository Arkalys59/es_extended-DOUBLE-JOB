# es_extended-DOUBLE-JOB
### This is the es_extended v1 final with the double job function

This resource was modified by me for my FiveM server called Eureka RP (https://discord.io/eurekarp if you want to enter), it's an Italian server set in Los Angeles.

## ! WARNING !
In my server I use the b1g_notify notification system slightly modified by me with some more events and notifications that also play a sound (via Interact sound https://github.com/plunkettscott/interact-sound), so for a complete functioning of es_extended you should download this system too from my GitHub (https://github.com/alebozz3/B1G-Notify-with-Sound-Notifications), otherwise you can restore the standard notifications by commenting on what I have modified.

## ! Installation !
```
- Replace your es_extended with this version
- Import into your DB
- Start the resource in the server.cfg
```

## ! Use !
I entered a command that is called by typing ```/ setjob2 [ID] [job] [grade]``` to set the second job of a player.
Any job can be set as a second job but if it is not configured it will not work.
For the configuration, just go to the files of any of your work and change the conditions that verify the player's work from PlayerData.job to PlayerData.job2. The resource also supports second salary both from a company (requires esx_society) and normally, but to have company management as a second job you will need to create an esx_society modification.
