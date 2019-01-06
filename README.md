# reprofile

Originally created to assist desktop analysts in removing corrupt user profiles from workstations while also ensuring all data is backed up for restoration once Windows has created a new profile for the user.

**Ensure you are _not_ logged in as the target profile before executing the script**

| Command | Description |
| --- | --- |
| `$Destination` | Set the profile backup path |
| `$ComputerName` | Set the host path (By default reprofile will use $env:computername) |
