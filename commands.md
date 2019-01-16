| Command       | Description                    |
| :------------:| :-----------------------------:|
|`git branch \| grep '\*' \| sed 's/* //'` | get current branch |
|`sed 's/[^0-9]//g'` | delete non-digit characters|
| `cat /dev/null > /Desktop/example.txt`      | empty a file   |
| `! docker > /dev/null 2>&1` | check if docker is installed |
|`! -d /etc/pki/rsyslog` | check if there is this directory |
|`[ -z "$KEY_ID" ]` | check if there is an ENV |
|`sed 's/.\(.*\)/\1/' \| sed 's/\(.*\)./\1/'` | strips quotes from string |
