


# Moderation

fault offers a wide range of moderation commands 


## Moderation Commands

| Command                                                           | Example                                                          | Usage                                                                                                                                                                                                                                                                        |

|-------------------------------------------------------------------|------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ban <user> [reason]                                     | `$ban @example spam`                                     | Ban members                                                                                |

| kick <user> [reason] | `$kick @example spam`                 | Kick Members                                                                                                     |

| cleankick [user ID/mention] (reason)                              | `/cleankick user:@Beemo#4570 reason:Spam`                       | Kicks the user and deletes their past 7 days of messages, notifying them through DMs and logging the incident.                                                                                                                                                               |

| case change duration [case ID] [new duration]                     | `/case change duration case:14 duration:4d`                      | Edits the duration of an existing moderation case. This will also edit the DM for the user who received the action to reflect the change. You may only edit your own cases unless you are a moderation manager                                                               |

| kick [user ID/mention] (reason)                                   | `/kick user:@Beemo#4570 reason:Spam`                            | Kicks the user, notifying them through DMs and logging the incident.                                                                                                                                                                                                         |

| modlogs [user ID/mention]                                         | `/modlogs user:@Beemo#4570`                                     | Shows all moderation logs for a user, including a link to each cases' action log and message archive.                                                                                                                                                                        |

| modnote [user ID/mention] [reason]                                | `/modnote user:@Beemo#4570 reason:Spam`                         | Adds a mod note onto the user's logs; This note is only visible to moderators, and does not DM the user or show when the user types `/mylogs`.                                                                                                                               |

| modstats [user ID/mention] (before:YYYY/MM/DD) (after:YYYY/MM/DD) | `/modstats user:@Beemo#4570 before:2021/01/01 after:2020/01/01` | Gets statistics of the specified moderator. You can optionally specify a before and/or after date to get stats for specific time periods. You must be a moderation manager or admin to use this command.                                                                     |

| mute [user ID/mention] (duration) (reason)                        | `/mute user:@Beemo#4570 duration:3h reason:Spam`                | Mutes the user, notifying them through DMs when the mute begins and ends and logging the incident. Not specifying a duration sets the mute to permanent.                                                                                                                     |

| presets view (variable)                                           | `/presets view name:spamming`                                    | Lists all available preset reason variables for the server. If a preset variable is specified, this command will list the correlated preset reason.                                                                                                                          |

| purge [amount <= 1000]                                            | `/purge amount:400`                                              | Mass-deletes the specified number of messages in the channel invoked. This command has a limit of 1000 messages, and may take a few seconds. You must be a moderation manager or admin to use this command.                                                                  |

| case change reason [case ID] [reason]                             | `/case change reason case:14 reason:Advertising`                 | Edits the reason of an existing moderation case. This will also edit the DM for the user who received the action to reflect the change. You may only edit your own cases unless you are a moderation manager or admin.                                                       |

| case revoke one [case ID] (reason)                                | `/case revoke one case:14 reason:Appealed`                       | Revokes the specified moderation case. This will prevent the case from showing on /modlogs and will edit the DM for the user who received the action to reflect that the action is revoked. You may only revoke your own cases unless you are a moderation manager or admin. |

| case revoke all [user ID/mention] (reason)                        | `/case revoke all user:@Beemo#4570 reason:Appealed`             | Revokes all cases tied to a user, preventing them from showing up on their moderation logs. You must be a moderation manager or admin to use this command.                                                                                                                   |

| saveban [user ID/mention] (duration) (reason)                     | `/saveban user:@Beemo#4570 duration:2d reason:Advertising`      | The same as `/ban`, except the user’s messages are not deleted.                                                                                                                                                                                                              |

| unban [user ID/mention] (reason)                                  | `/unban user:@Beemo#4570 reason:Reformed`                       | Unbans the user, attempting to DM them and logging the incident.                                                                                                                                                                                                             |

| unmute [user ID/mention] (reason)                                 | `/unmute user:@Beemo#4570 reason:Reformed`                      | Unmutes the user, notifying them through DMs and logging the incident.                                                                                                                                                                                                       |

| whois [user ID/mention]                                           | `/whois user:@Beemo#4570`                                       | Gets information regarding a user in the server, such as account age, join date, join position, and roles.                                                                                                                                                                   |

| warn [user ID/mention] (reason)                                   | `/warn user:@Beemo#4570 reason:Spam`                            | Warns the user, notifying them through DMs and logging the incident.                                                                                                                                                                                                         |
