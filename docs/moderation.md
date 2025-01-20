## Actions

There are several actions that can be performed by Moderators, such as:
- **Strike**
- **Kick**
- **Timeout**
- **Ban**

Additionally, message **purging** is available.

**Server groups** allow multiple servers to perform same tasks, such as **banning** and **kicking** same user from all of them.  

### Punishment duration

Duration is inputted as: `10d` = '10 days' or `1w3d` = '1 week and 3 days'.  
- `m` - minutes
- `h` - hours
- `d` - days
- `w` - weeks

### Punishment proof

Some commands accept image proofs, which are viewable in moderation log. **Only .jpeg/.png images lower than 4MB can be attached!**

## Main commands

Name                             | Example                             | Usage
-------------------------------- | ----------------------------------- | --------------------------
**ban <@User\|ID> [duration] [reason] [proof] [purge messages?] [dm user?]** | `/ban @axelot 10d 'Bad behavior'` | Bans the member from this server.
**unban <ID> [reason]** | `/unban @axelot 'appeal'` | Remove ban for this user.
**mute <@User\|ID> <duration> [reason] [proof]** | `/mute @axelot 6h 'Bad behavior'` | Timeout a member.
**unmute <@User\|ID> [reason]** | `/unmute @axelot` | Remove a timeout from this member.
**kick <@User\|ID> [reason] [proof] [dm user?]** | `/kick @axelot 'Bad behavior'` | Kicks a member.
**strike <@User\|ID> <severity (1-3)> <reason> [proof]** | `/strike @axelot 1 'Bad behavior'` | Strike a member. Severity from 1 to 3 strikes.

## Additional commands

Name                             | Example                             | Usage
-------------------------------- | ----------------------------------- | --------------------------
**purge [@User] [count]** | `/purge @axelot 20` | Purges messages. Specified user's messages can be purged. By default, purges up to 60 messages.
**case <case ID>** | `/case 123` | View case information.
**duration <case ID> <duration>** | `/duration 123 10d` | Change punishment's duration, like mute or ban.
**reason <case ID> <reason>** | `/reason 123 'Very bad behavior'` | Change action's reason.
**modlogs [@User] [page] [only active?]** | `/modlogs @axelot` | Show user's punishments.
**modstats [@User] [start date] [end date]** | `/modstats @mod` | Show actions performed by specified user.
**strikes [@User]** | `/strikes @axelot` | View user's strikes.
**delstrike <@User>** | `/delstrike @axelot` | Delete user's strike.
**clearstrikes <@User>** | `/clearstrikes @axelot` | Delete all user's strike. **Only for admins.**
