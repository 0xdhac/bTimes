# bTimes 2.0 by blacky (0xdhac on github)
I know it's already leaked elsewhere but I'm putting this on my own Github for portfolio reasons. Timer for both CS:S and CS:GO bhop servers. Probably outdated in various ways at this point.

### How to install
Import the *database.sql* to your SQL database
Drag and drop the server upload files to your server, and edit databases.cfg to have this.
```
	"timer"
	{
		"driver"		"default"
		"host"			"hostnamehere"
		"database"		"dbnamehere"
		"user"			"usernamehere"
		"pass"			"passwordhere"
		//"timeout"		"0"
		"port"		   	"porthere"
	}
```