## Access Commands

!> <span class="admin">Administrator</span> access required for adding/removing **roles**.   
<span class="owner">Owner</span> access required for adding/removing **operators**.

Name                             | Example                             | Usage
-------------------------------- | ----------------------------------- | --------------------------
**access add role <@Role> <Access level>** | `/access add role @Mods 'Moderator'` | Assign the specified access to the selected role.
**access remove role <@Role>**   | `/access remove role @Mods`         | Remove any access from the selected role.
**access add operator <@User>**  | `/access add operator @axelot`      | Assign the specified user as a server operator.
**access remove operator <@User>** | `/access remove operator @axelot` | Remove operator access from the specified user.
**access view**                  | `/access view`                      | View assigned accesses to roles and users.

### Access Levels

?> Higher levels inherit permissions from all previous levels. (ex, Moderators also are exceptions to strikes, can manage roles and tickets.)

Access                                   | Target     | Description
---------------------------------------- | ---------- | -------------
User                                     | -          | Everyone, default level
<span class="exception">Exception</span> | Role       | Exceptions - are roles that will not receive auto-punishment from strikes
<span class="helper">Helper</span>       | Role       | Helper - can interact with tickets and manage roles
<span class="mod">Moderator</span>       | Role       | Moderator - can use moderation commands and other
<span class="admin">Administrator</span> | Permission | Administrator - can manage bot and other server settings
<span class="op">Operator</span>         | User       | Server Operator - can manage server Groups
<span class="owner">Owner</span>         | -          | Server owner
