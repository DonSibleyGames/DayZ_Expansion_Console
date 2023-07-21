

# DayZ Expansion Console
The DayZ Expansion mod exteriors and Interiors converted to run on console DayZ

1. To use the json files on your DayZ Console server, just add the file you want to run to the 'custom' folder on your server.
2. Then in cfggameplay.json add the name of the file you added like this:
```json
"WorldsData":
	{
		"lightingConfig": 1,
		"objectSpawnersArr": ["./custom/TheFileIAddedNameGoesHere.json"],
		"environmentMinTemps": [-3.0, -2.0, 0.0, 4.0, 9.0, 14.0, 18.0, 17.0, 12.0, 7.0, 4.0, 0.0],
		"environmentMaxTemps": [3.0, 5.0, 7.0, 14.0, 19.0, 24.0, 26.0, 25.0, 21.0, 16.0, 10.0, 5.0],
		"wetnessWeightModifiers": [1.0, 1.0, 1.33, 1.66, 2.0]
	},
 ```
3. Save and make sure that 'Enable cfggameplay.json' checkbox is ticked in your Nirtado settings page.


# Donations
I've been asked by a few people how to donate to me.

I don’t  really like promoting that sort of thing, but here are a couple of ways to do so if you wish to.
Costs will go towards DayZ server costs and general content creation/streaming.

Thank you!

**Paypal:**
https://paypal.me/DonSibleyGames

**Youtube Membership:**
https://www.youtube.com/channel/UCI9Wh1Nl1i_Sfz_AT3PTVcg/join

Check the different levels of Youtube membership or the type of perks you can get.
