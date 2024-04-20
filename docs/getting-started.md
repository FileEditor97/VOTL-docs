## Navigating

Each command module has their own page which can be found on the sidebar.

Syntax            | Definition                                                                                        
 ---------------- | ------------------------------------------------------------------------------------------------- 
`<foo>`           | This option is mandatory                                                                        
`[foo]`           | This option is optional                                                                         
`[foo\|bar]`      | This option is optional so you can either use **foo** or **bar**, or don't specify it at all    

Some options may accept different types of inputs, like Roles and User mentions.

## Basic Configuration

Bot is ready for use once it has joined the server, but for some modules setup is required. 

- ### Verification
Setup verification role with `/verifyrole <@Role>`. Next, setup verfification panel by `/vfpanel text` and `/vfpanel image <image URL>`.
Create panel with `/vfpanel create <#Channel>`.


- ### Custom voice channels
Create new category and voice channel with `/setup voice create` **or** select existing voice channel `/setup voice select <#Channel>`.
Custom voice channels can be managed by user using command `/voice` or by panel. To create control panel use `/setup voice panel <#Channel>`.


- ### Logging
Setup logging with `/logs manage`. To enable log's category type `/logs manage enable <type> <#Channel>`. To view current logging settings type `/logs manage view`.
Certain channel and categories can be excluded from logs (such as message deletion) using `/logs exceptions add <#Channel>`.


- ### 
