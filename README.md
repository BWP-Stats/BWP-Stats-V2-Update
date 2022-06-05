# [BWP-Stats](https://discord.com/api/oauth2/authorize?client_id=926814210321707028&permissions=277025442816&scope=bot%20applications.commands) V2 Update Information

<h2 id="contents">Contents</h2>

- [Update Information](#update-information)
  - [Major Updates](#major-updates)
    - [Profile Changes](#profile-changes)
    - [Guild Changes](#guild-changes)
    - [Estimate Changes](#estimate-changes)
    - [Help Changes](#help-changes)
  - [Minor Updates](#minor-updates)

<h2 id="update-information">Update Information</h2>

<h2 id="major-updates">Major(ish) Updates</h2>

<h3 id="profile-changes">Profile Changes:</h3>

- Added text shadow to all text ([Example](https://imgur.com/a/uBdEqhL))
- Added extra space between the statistic name and the statistic amount (To avoid overlapping)
- Stars are now moved to the right if they have < 3 characters
- Added profile as a user command ([Example](https://i.imgur.com/wmAa4oF.gif))
- Added an autocomplete for the IGN option. (Will show up with previously requested IGNs so you don't have to type the whole thing)
- Fixed bugs with some ranks

<h3 id="guild-changes">Guild Changes:</h3>

- An image is now used to show guild stats ([Example](https://imgur.com/a/hYnxuYJ))
- An image is now used to show the guild member list ([Example]())
- The member list and general statistics are now seperate
- Improved the speed of getting stats on the `info` option

<h3 id="register-cmd">Register Command</h3>

- Added a `/register` command to link your minecraft account with your discord account
- This is linked to the in game bot (`voxylstats`) which is what will be used for verifying your minecraft account
- This will be used for user commands ([Example](https://i.imgur.com/wmAa4oF.gif))
- This will be used for daily, weekly & monthly historic commands ([Information](#historic-cmds))

<h3 id="historical-cmds">Historical Commands</h3>

- Added historical commands
  - `/daily` - Shows the stats you gained in a 24 hours period ([Example](https://imgur.com/a/zB1Qqaw))
  - `/weekly` - Shows the stats you gained in a 7 day period ([Example](https://imgur.com/a/zB1Qqaw))
  - `/monthly` - Shows the stats you gained in a 30 day period ([Example](https://imgur.com/a/zB1Qqaw))

- Added historical settings commands
  - These commands allow you to reset your historical reset time & enable & disable historical tracking
  - `/historical tracking enable` - Enable your historical tracking (Requires you to be registered)
  - `/historical tracking disable` - Disable your historical tracking (Requires you to be registered)
  - `/historical tracking reset` - Reset the historical tracking reset time to now (Requires you to be registered)

<h3 id="leaderboard=changes">Leaderboard Changes</h3>

- Leaderboard is now an image ([Example](https://imgur.com/a/4MRZeQt))
- The inputted IGN is now highlighted so it is easier to see ([Example](https://imgur.com/a/4MRZeQt))
- Added arrows to change pages
- There is now 10 pages instead of 5

<h3 id="estimate-changes">Estimate Changes:</h3>

- An image is now used to show estimated statistics of a user ([Example](https://imgur.com/a/yp2hIXb))
- The maximum requested level has been lowered
- Removed the `stats until` section

<h3 id="guildleaderboard-changes">Guild Leaderboard Changes:</h3>

- `/guildleaderboad` is now shown as an image ([Example](https://imgur.com/a/c4VUqy1))
- The leaderboard is now updated every 20 minutes (Before we created a new request to the [API](https://api.voxyl.net/) every time the command was run)

<h3 id="help-changes">Help Changes</h3>

- `/help` is now a lot easier to read and go through ([Example](https://i.imgur.com/uJNWxi5.gif))
- Now uses buttons to move between categories ([Example](https://i.imgur.com/uJNWxi5.gif))
- Removed the `command` option when running `help` (Not needed)

<h2 id="minor-updates">Minor Updates</h2>

- Updated some small things in `/botinfo` (Now shows commands run & some other stuff)
- Updated the `/listweights` values
- Fixed `/status` showing in servers it shouldn't
- Fixed `/bwpinfo` showing minecraft formatting/colour codes in the description option
- Added a [channel](https://canary.discord.com/channels/926955080010301480/965352171040276500) in our [discord server](https://discord.gg/fBnfWXSDpu) to show level leaderboard updates
- Added a [channel](https://canary.discord.com/channels/926955080010301480/965360224003326033) in our [discord server](https://discord.gg/fBnfWXSDpu) to show weighted wins leaderboard updates


