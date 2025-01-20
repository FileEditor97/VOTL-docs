!> Requires <span class="admin">Administrator</span> access.

## Enable/Disable modules

Name                    | Example               | Usage
----------------------- | --------------------- | --------------------------
**module enable**       | `/module enable`      | Enable select module.
**module disable**      | `/module disable`     | Disable select module.
**module show**         | `/module show`        | Show current module statuses.

### Modules

Name                | Commands
------------------- | ----------
Webhook commands    | `/webhook`
Moderation category | All commands from **moderation category**, excluding strikes
Strike punishments  | `/strike`, `/strikes`, `/delstrike`, `/clearstrikes`, `/autopunish`
Verification        | `/vfpanel`, `/verifyrole`,
Tickets             | All commands from **ticketing category**, role requests
Custom VCs          | `/voice`
Report function     | *Context menu on messages (Report message)*
Role management     | `/role`, `/temprole`, `/persistent`
Games               | `/game`, `/gamestrike`