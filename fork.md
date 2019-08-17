This fork was created so that it could use the forked build at located at https://github.com/meanlucy/rileylink_ios that has a modification that allows the device to beep.

The only changed files are in the omnipod-testing branch: **Cartfile** and **Cartfile.resolved** 

This change allows the code to pull this dependency from the fork.

To build this app, clone the repository and build in Xcode. Note that you may need to delete the Cartfile.resolved if it has been used from a different fork.
