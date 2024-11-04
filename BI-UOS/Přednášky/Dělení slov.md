- proměnná `IFS` - if separator
```
#!/bin/bash

OLDIFS="$IFS" # remember current value of IFS
IFS=":" # set new value of IFS

# Read lines from the file / etc / passwd
while read name foo uid gid comment home shell
do
	echo "name = $name uid = $uid"
done < /etc/passwd

IFS="$OLDIFS" # set previous value of IFS
```