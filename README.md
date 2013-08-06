gnome3-launchers
================

gnome3 activity/overlay launchers

for Debian Wheezy, symlink these into /usr/share/applications

a note about restart.sh
this requires that the shutdown command is executable without a sudoer password
i accomplished this with a new group, adding myself to the group, and modifying /etc/sudoers to allow that group 'shutdown' execution without a password
