# p4ignore
Sample P4IGNORE files for different project types such as Unreal Engine and Unity.

This is intended to be a suitable equivalent to files found in: https://github.com/github/gitignore

# Linux Usage

Ensure that your P4IGNORE environment variable is appropriately set. E.g.

    export P4IGNORE=.p4ignore.txt   # Bash

See also: https://www.perforce.com/manuals/v19.2/cmdref/Content/CmdRef/envars.html

On Windows the following should be done in a command prompt to save it to your registry settings.
This will still be there next time you login.

    p4 set P4IGNORE=.p4ignore.txt

Then copy the relevant file for your project to the root of your client workspace. Make any adjustments to it
that you required.

*It is normal to check-in/submit these files for your project so that your colleagues use the same settings*
