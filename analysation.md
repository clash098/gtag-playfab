# Authentication
### Authenticate Game Server With Custom ID 🟠
This Method Requires An Entity Token

### Delete 🟠
This Method Requires An Entity Token

### Validate Entity Token 🟠
This Method Requires An Entity Token 

### Get Entity Token 🔴
This Method Is Not Authorised
Explanation: Larson used this to regenerate tickets. Ticket > Entity Token > Ticket

# Client
## Account Management

### Add Or Update Contact Email 🟢
Successfully adds an email address to your account (Can't be identified by this)

### Get Account Info 🟢
Gets the information for the account you either supply or by default the information for the account you use to send the request

### Get Player Combined Info 🟢
Allows you to get different data on an account by its playfab id, you can get more info on yourself by not including the playfab id field

### Get Player Profile 🟢
Gets information about the players profile using the given params

### Update User Title Display Name 🟢
Doesn't update ingame name only playfab name. Resets when your game is started

### Report Player 🟢﻿﻿
Reports a player from there playfab id, not sure if it works

### Add Generic ID 🟠
Requires a Generic Id which needs a valid generic service identifier

### Get PlayFab IDs From... 🟠
All of these are either blocked or return with a useless other than steam which returns with an id

### Add Username Password 🔴
This Method Is Not Authorised

### Link/Unlink ... Account 🔴
You can't link or unlink an account, not authorised.

### Update Avatar Url 🔴
This Method Is Not Authorised

### Send Account Recovery Email 🟠﻿﻿
Since you can't be identified by your email, it can't send you an email
## Advertising (Blocked)
### Attribute Install 🔴﻿﻿
This Method Is Not Authorised

### Get Ad Placements 🔴﻿﻿
This Method Is Not Authorised

### Report Ad Activity 🔴﻿﻿
This Method Is Not Authorised

### Reward Ad Activity 🔴﻿﻿
This Method Is Not Authorised
﻿
## Analytics (Blocked)
### Report Device Info 🔴
This Method Is Not Authorised

### Write Character Event 🔴
This Method Is Not Authorised

### Write Player Event 🔴
This Method Is Not Authorised

### Write Title Event 🔴
This Method Is Not Authorised

## Authentication
### Get Photon Authentication Token 🟢
Successfully grabs the Photon Authentication Token, this will be given to the boosters

### Get Title Public Key 🔴﻿﻿
This Method Is Not Authorised 

### Register PlayFab User 🟠
This generates an account but it's instantly banned

### Set Player Secret 🔴
You need to find there rsa key or generate it wich will take 2 million years

### Login With... 🔴
You can't login with anyhting other then a steam ticket or potentially a custom id

## Character Data (Blocked
### Get Character Data 🔴
Requires a charecter id

### Get Character Read Only Data 🔴
Requires a charecter id

### Update Character Data 🔴
Requires a charecter id

## Characters
### Get All Users Characters 🟠
Responds with all your characters but characters is empty

### Get Character Leaderboard 🔴
Needs a statistic to find leaderboard pos

### Get Character Leaderboard 🔴
Needs a statistic
