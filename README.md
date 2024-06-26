# symlink-to-inaccessible - Example repo with symlink to often-inaccessible Windows path

This is a simple example repository containing a symbolic link to a path that often exists but is in accessible, if using a desktop version of Windows. There are many possible variations on this, all imperfect. The path used here points to
a specific directory, which usually exists, inside `\Program Files\WindowsApps`. The contents of `WindowsApps` are inaccessible to regular users on Windows, including administrators at least if UAC is enabled.

To be used to manually test Git-related software for how such symbolic links are treated, this should be cloned on a Windows system that has the Microsoft Store (server editions do not have it), and on the same drive as the system drive (since the path given is drive-relative).
