# [Any] Ninja Leap
#### Current Version: 1.0.2  

## Description:
Allows players to leap through the air with a key-bindable command.
**Video:**  [http://www.youtube.com/watch?v=1CgqWlwzleM](http://www.youtube.com/watch?v=1CgqWlwzleM)    

*Supports all SourceMod compatible games.*

## Commands:
-   **ninjaleap [Power] [Angle]**  - Leap through the air!  
    Power and Angle are optional, and will use the default values that can be set in a cvar below.
-   **leap**  - Same as above

### Examples:
-   leap 1500 -45
-- Would launch the player upwards at a 45 degree angle with 1500 force.
-   ninjaleap 1000 -90  
    --Would launch the player straight up at 1000 force.



## Cvars:
-   **sm_ninjaleap_version -** Plugin Version
-   **sm_ninjaleap_enable "1" -** Enable/Disable the plugin
-   **sm_ninjaleap_power "1000"**  -The default force to use if the player doesn't specify.
-   **sm_ninjaleap_angle "-30"**  - The default angle to use if the player doesn't specify.
-   **sm_ninjaleap_log "0"**  - Whether or not to log leap actions.
-   **sm_ninjaleap_admin "0"**  - Set to 1 to make the plugin admin-only.


**Permissions overrides:**
Use  **sm_ninjaleap_override**  in your overrides config to change the flag needed for admins when in admin-only mode.  
Default flag is Slay.  

## Install Instructions:
1.  [Drag and drop](http://www.youtube.com/watch?v=WLPa4Fsh4ak) to your plugins folder


## Version History:

-   **V1.0.0**
    -   Initial Release
-   **V1.0.1**
    -   Stupid typo with CheckCommandAccess
-   **V1.0.2**
    -   Fixed  [this bug](https://forums.alliedmods.net/showpost.php?p=2010374&postcount=16)
