# global_vars

*Author: Ruthgul*<br />

### Store and retrieve variables for use by other plugins

------

#### Features:

- Store and retrieve non-persistent variables which can be shared between plugins.

#### Aliases:
- **var** \<name>
  > List the contents of the target variable shared by this plugin.

- **vars**
  > List the contents of all variables shared by this plugin.

#### Public Interfaces:
```get_global_var( string name) : string
set_global_var( string name, string value) : void```
