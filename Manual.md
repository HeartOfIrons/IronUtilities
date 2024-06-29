# IronUtilities

### What is IronUtilities?
Iron Utilities, or IrUtil is a Roblox-based Utility all-in-one module. It covers various functions and utilities right in one single module for use in command line and advanced scripts without much knowledge of how to use.

### What functions are there?
Currently in the newest release, there are 51 functions.
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
```
