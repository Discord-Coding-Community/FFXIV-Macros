# Class Menu

A series of Macros for use with creating a collapsable Class Menu to simplify build switching.


## Usage

 - Simply replace `[CLASS INITIALS]` with the initials for the class of which you are copying the shared hotbar from.
    - Example:
    ```cs
        /hotbar copy BRD 10 share 10
        /hotbar copy BRD 9 share 9
    ```
 - Next, add all of the Gear Set Macros to both the shared and unshared versions of hotbars 9 and 10, then share, unshare, and reshare both hotbars 9 and 10.
 - Once done hide hotbars 9 and 10 and add the Class Menu Macro to a visible shared hotbar.

## Notes

 - This Macro set can be finicky when setting up, so sometimes unsharing and re sharing hotbars 9 and 10 before attempting to click the Class Menu Macro may be needed for it to save.
 - Make sure the shared and un shared versions hotbars 9 and 10 are completely identical to each other.
 - Make sure you are making these on the same class that the Class Menu copies the Gear Set Macros from for it to save.
 - Do **NOT** include the brackets `[]` in the Macro.
 - This Macro set utilizes the [Hotbar Macro Template](https://github.com/Discord-Coding-Community/FFXIV-Macros/tree/master/Miscellaneous/Hotbar%20Macro%20Template).