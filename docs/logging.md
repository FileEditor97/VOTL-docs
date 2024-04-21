?> Logs are sent using Webhooks crated by this bot. For each event type new Webhook is created. You can rename, change avatar and location for those Webhooks in Integration settings.

## Logging setup

Name                             | Example                             | Usage
-------------------------------- | ----------------------------------- | --------------------------
**logs manage enable \<Type> <#Channel>** | `/logs manage enable 'Role logs' #logs-role` | Enable selected type events logging in selected channel.
**logs manage disable \<Type \| ALL>**  | `/logs manage disable 'Role logs'`  | Disable selected type or all events logging.
**logs manage view**             | `/logs manage view`                 | View logging settings - enabled events and channels.
**logs exceptions add <#Channel \| Category>** | `/logs exceptions add #secret-chat` | Exclude channel or category from (message) logging.
**logs exceptions remove \<ID>** | `/logs exceptions remove '123456789123456'` | Remove target from logging exceptions.
**logs exceptions view**         | `/logs exceptions view`             | View logging exceptions.

### Event types

Type                  | Events
--------------------- | -------------
**Moderation logs**   | Ban, Kick, Ban remove, Timeout, Timeout remove, Strikes, Blacklists, Reason/Duration change
**Role logs**         | Role creation/update/deletion, Temporary roles
**Group logs**        | All group actions
**Ticket logs**       | Ticket creation/deletion
**Server logs**       | Access and Module actions, Emojis, Stickers
**Channel logs**      | Channel creation/update/deletion/permissions
**Member logs**       | Member join/leave, Member roles change, Member nickname change
**Voice logs**        | Voice mute and deafen
**Message logs**      | Messages update, deletion and bulk deletion
