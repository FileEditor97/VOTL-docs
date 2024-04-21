Custom voice channel can be created by joining defined voice channel (created by bot or selected). Each user may only have 1 custom voice channel under theirs control.

Channel's name and user limit is stored for each user when changed and default name and limit may be set by server's administration. Channel's owner can control theirs voice channel manualy thru channel settings, by commands `/voice` or using control pannel `/setup voice panel`.

## Setup commands

Name                             | Example                 | Usage
-------------------------------- | ----------------------- | --------------------------
**setup voice create**           | `/setup voice create`   | Creates new category and voice channel.
**setup voice select <#Channel>**| `/setup voice select #join` | Select channel to be used for custom voice channel creation.
**setup voice panel <#Channel>** | `/setup voice panel #panel` | Creates contol panel for custom voice channels.
**setup voice name \<text\>**    | `/setup voice name 'My channel'` | Sets default name for new voice channels.
**setup voice limit \<number\>** | `/setup voice limit 10` | Sets default user limit for new voice channels.

## Control commands

Name                             | Example                 | Usage
-------------------------------- | ----------------------- | --------------------------
**voice lock**                   | `/voice lock`           | Locks the channel from everyone (can't join).
**voice unlock**                 | `/voice unlock`         | Unlocks the channel from everyone (can join).
**voice ghost**                  | `/voice ghost`          | Ghosts the channel from everyone (can't view).
**voice unghost**                | `/voice unghost`        | Unghosts the channel from everyone (can view).
**voice name set \<text\>**      | `/voice name set 'My channel'` | Set owned voice channel's name.
**voice name reset**             | `/voice name reset`     | Reset owned voice channel's name to server's default.
**voice limit set \<text\>**     | `/voice limit set 10`   | Set owned voice channel's user limit.
**voice limit reset**            | `/voice limit reset`    | Reset owned voice channel's limit to server's default.
**voice claim**                  | `/voice claim`          | Claim voice channel if it's owner has left it.
**voice permit \<@Role \| @Member\>** | `/voice permit @axelot` | Permit user or role to join voice channel if it's locked or ghosted.
**voice reject \<@Role \| @Member\>** | `/voice reject @axelot` | Deny user or role access to join voice channel.
**voice perms view**             | `/voice perms view`     | View voice channel's permissions (who can view or join).
**voice perms reset**            | `/voice perms reset`    | Reset voice channel's permissions (to category default).

## Control Panel

?> Voice channel owners can delete theirs channel by pressing 'Delete channel' on controls panel.

![Control panel](_images/voice-panel.png ':size=75%')

