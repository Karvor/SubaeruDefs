# Subaru ECU Definitions

This repository is used to develop Subaru ECU definitions for use with:
*   Romraider http://www.romraider.com
*	ECUFlash http://www.tactrix.com

Discussion thread at RomRaider for this repo: http://www.romraider.com/forum/viewtopic.php?f=34&t=8635

# Branches:
*	Stable branch: Contains the latest NON-experimental definitions. These definitions have been thoroughly debugged and tested.
*	Beta branch: Formerly "Experimental". Contains definitions with finalized 'bases' that are newly defined for a particular rom. Considered safe for use by advanced users.
*	Alpha branch: Contains definitions that are under active development. **DO NOT USE THIS BRANCH UNLESS YOU ARE A DEVELOPER OR A DEVELOPER'S TESTER**

Benefits of using Git:
*	Better tracking of definition history/changes.
*	Easier to implement standardization of new tables, scalings, descriptions, formats, etc.
*	Ease of use for end users, no more scouring a forum to find definitions or get an updated def.
*	Easier to collaborate and stay organized.
*	By pointing RomRaider or ECUFlash at the local repo, you can easily switch between different branches for quick tests/comparisons.

#WARNING: These definitions are EXPERIMENTAL!

These definition files are created as the result of the extremely
complex and time consuming process of reverse-engineering the factory ECU.
Because of this complexity, it is necessary to make certain assumptions and,
therefore, it is impossible to always deal in absolutes in regards to
representations made by these definitions. In addition, due to this complexity
and the numerous variations among different ECUs, it is also impossible to
guarantee that the definitions will not contain errors or other bugs. What this
all means is that there is the potential for bugs, errors and misrepresentations
which can result in damage to your motor, your ECU as well the possibility of
causing your vehicle to behave unexpectedly on the road, increasing the risk of
death or injury. Modifications to your vehicle's ECU may also be in violation of
local, state and federal laws. By using these definition files, either directly
or indirectly, you agree to assume 100% of all risk and RomRaider's creators and
contributors shall not be held responsible for any damages or injuries you
receive. This product is for advanced users only. There are no safeguards in
place when tuning with RomRaider. As such, the potential for serious damage and
injury still exists, even if the user does not experience any bugs or errors. As
always, use at your own risk.

