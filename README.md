SteamTracks Changelog
===========

#### 2014-02-28

- When users join SteamTracks they will now be asked to add the bot and not the other way around. This should reduce or eliminate the problem where users don't receive the bot's friend request

#### 2014-02-23

- Changed the bot distribution system to be properly queued. This should reduce missed friend requests from your bot to a minimum

#### 2014-02-22

- Updated the bot infrastructure, Dota 2 profile should now be gathered again as expected, this update will take around 24 hours to fully propagate
- Reduced the Dota 2 profile update from 12 hours to every 24 hours. This change was necessary in order to keep server costs viable


#### 2014-02-15

- Added variable `privateProfile` to the dota 2 profile hash, values are 0 (profile is NOT private) and 1 (profile IS private). This variable is available for all apps that have at least one permission info from the dota 2 section
