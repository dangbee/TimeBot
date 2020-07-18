# TimeBot
A simple time bot for Discord.

# Commands

!time \<query\/@member>
- The query parameter is a city, town or country.
- The @member parameter is a member who has set their time using the !settime command.
- You can have no parameter for !time and it'll return the time you set for yourself.

!settime \<query\>
- The query parameter is a city, town or country.
- This command will set the timezone of the member who used it.

!removetime
- Remove the set time for yourself from our database.
- Effectively removes you from our infrastructure, useful to remove your data from our systems.