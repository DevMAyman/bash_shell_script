##[Lab 2]<br />
#q1 - <br />
<img src="./pics/01-01.png" height="500" width="700" />
<img src="./pics/01-02.png" height="500" width="700" />
--------------------------------------------------------
#q2 - <br />
<img src="./pics/02-01.png" height="400" width="600" />
<img src="./pics/02-02.png" height="400" width="600" />
<img src="./pics/02-03.png" height="400" width="600" />
<img src="./pics/02-04.png" height="400" width="600" />
<img src="./pics/02-05.png" height="400" width="600" />
<img src="./pics/02-06.png" height="400" width="600" />
---------------------------------------------------------
#q3 - <br />
<img src="./pics/03-01.png" height="400" width="600" />
-----------------------------------------------------------
#q4 - <br />
<img src="./pics/04-01.png" height="400" width="600" />
<img src="./pics/04-02.png" height="400" width="600" />
<img src="./pics/04-03.png" height="400" width="600" />
----------------------------------------------------------
#q5 - <br />
```
#! /usr/bin/bash
ls $1
```
----------------------------------------------------------
#q6 - <br />
```
#! /usr/bin/bash
ls $1
```
-----------------------------------------------------------
#q7 - <br />
```
#! /usr/bin/bash
if [ -f "$1" ]; then
    echo "It is a file."
elif [ -d "$1" ]; then
    echo "It is a directory."
else
    echo "It is neither a file nor a directory, or the path does not exist."
fi

stat -c "%A" "$1"
```
-----------------------------------------------------------
#q8 - <br />
```
#! /usr/bin/bash
read -p "Enter your logname" logname
ls -l /home/"$logname"
cp /home/"$logname" /temp
ps -u "$logname"
```
-----------------------------------------------------------
