Verification is a simple button, that assigns @Role.  
There are some commands for customizing verification panel (embed).

## Setup commands

!> Requires <span class="admin">Administrator</span> access.

Name                             | Example                 | Usage
-------------------------------- | ----------------------- | --------------------------
**verifyrole <@Role>**           | `/verifyrole @verified` | Set verification role.
**vfpanel text**                 | `/vfpanel text`         | Set the text for embed panel.
**vfpanel image \<URL>**         | `/vfpanel image 'https://imgur.com/...'` | Set the image URL for embed panel.
**vfpanel preview**              | `/vfpanel preview`      | Preview verification panel embed.
**vfpanel create <#Channel>**    | `/vfpanel create #verify-here` | Send panel to the selected channel.

?> Embed color is set by `/setup color`.