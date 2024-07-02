# IronUtilities

### What is IronUtilities?
Iron Utilities, or IrUtil is a Roblox-based Utility all-in-one module. It covers various functions and utilities right in one single module for use in command line and advanced scripts without much knowledge of how to use.

### What functions are there?
Currently in the newest release, there are 51 functions.

--**LOGGING**--

### CUTIL.LogMessage() - (Message,Level,Custom)

*DESCRIPTION*

Logs a message with an optional severity level and timestamp.

*PARAMETERS*

Message - A string containing the message to log. (Ex. "Hello World!") 
Level (Opt) - A string representing the log level. (Ex. "INFO" or "ERROR"). Defaults to Strg.LogLevels.INFO.
Custom (Opt) - A boolean indicating whether to return the log entry instead of printing it. Defaults to false.

CUTIL.FilterLogs() - (Level)

*DESCRIPTION*

Filters the log entries by the specified log level and returns a table containing the matching entries.

*PARAMETERS*

Level - A string representing the log level to filter by (Ex. "INFO").

CUTIL.ClearLogs() - (Level)

*DESCRIPTION*

Clears log entries with the specified log level. If no level is specified, all log entries are cleared.

*PARAMETERS*

Level (Opt) - A string representing the log(s) to clear by level (Ex. "INFO"). If nil or unrepresented, all logs are cleared.

--**BASIC UTILITIES**--
```
CUTIL.FindInstance() - (Location,Instance,Recursive)
*DESCRIPTION*
Finds an instance or child (if recursive) of the exact name given on Par2 (Instance Parameter) and returns it, otherwise returns nil.
*PARAMETERS*
Location - An instance of where you want to search. (Ex. game.Workspace)
Instance - A string of what you want to find. (Ex. "Object204")
Recursive (Opt) - Wether or not you want to search deeper. (Ex. true)

CUTIL.Search() - (Location,Item,Action)
*DESCRIPTION*
Searches the entirety of the Location given (Location Parameter) and does an action given.
*PARAMETERS*
Location - An instance of where you want to search. (Ex. game.Workspace)
Item - An instance or string of what you want to collect. Optionally you can do "AllItems" to collect all. (Ex. game.Workspace.Baseplate OR "Baseplate")
Action - The action you want to perform after collecting item(s). (Ex. "Delete" OR "Highlight" OR "Return")

CUTIL.Create() - (Location,Asset,Properties)
*DESCRIPTION*
Creates an instance/asset in the Location given (Location Parameter) and gives it properties.
*PARAMETERS*
Location - An instance of where you want to create the instance/asset. (Ex. game.Workspace)
Asset - A string of the selected instance you want to create. (Ex. "Part" OR "MeshPart" OR "Model")
Properties - A table of what you want to add to the instance/asset. (Ex. {} OR {Transparency = 1, CanCollide = false})

CUTIL.Edit() - (Location,Asset,Properties)
*DESCRIPTION*
Edits the properties of a specified asset/part within the given location.
*PARAMETERS*
Location - An instance where the asset is located (Ex. game.Workspace).
Asset - A string representing the name of the asset to edit.
Properties - A table containing the properties to set on the asset. (Ex. {} OR {Transparency = 1, CanCollide = false})
```
--**BIT UTILITIES**--
```
CUTIL.Bxor() - (Alpha,Beta)
*DESCRIPTION*
Acts as an XOR gate, but for Bitwise. For more information: https://en.wikipedia.org/wiki/Bitwise_operation
*PARAMETERS*
Alpha - Operand one to compute against Beta / With Beta
Beta - Operand two to compute against Alpha / With Alpha

CUTIL.Band()
*DESCRIPTION*
Acts as a AND Gate, but for Bitwise. For more information: https://en.wikipedia.org/wiki/Bitwise_operation
*PARAMETERS*
Alpha - Operand one to compute against Beta / With Beta
Beta - Operand two to compute against Alpha / With Alpha
```
