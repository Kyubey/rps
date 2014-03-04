rps
===
{
    "name": "RPS",
    "altname": "RockPaperScissors",
    "author": [
	"Joeypals",
	"Xtina",
	"Ariana_Grande",
	"obey to kyubey"
    "minplayers": 3,
	"nonPeak": true,
	"ticks": {
		"standby": 20
	},
    "summary": "One day, some children were arguing about who was the best at Rock-Paper-Scissors. After a massive uproar, a dark child said ''Hey, just go into teams. I'll be alone. Team that wins is the best'', and thus started the Super Mega Ultra Rock-Paper-Scissors tournament! In as much as teams of 4, the teams will try to outdo each other and try to be the last one standing! A/N This theme runs on an HP system based on effectiveness. Good hit means 2HP for the opponent lost, bad hit means none lost, hitting the same type will cause you both to lose 1HP. If you have any comments, questions, concerns, or bugs, please contact either obey to kyubey or Joeypals/Ariana_Grande/Xtina.",
    "altname": "Rock, Paper, Scissors",
    "sides": [
        {
            "side": "warm",
            "translation": "Warm Colours",
            "winmsg": "±Foot: With fiery determination, ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "cold",
            "translation": "Cold Colours",
            "winmsg": "±Foot: Through icy determination, ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "oddball",
            "translation": "Oddball Colours",
            "winmsg": "±Foot: By being themselves and having fun, ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "voodoo",
            "translation": "Voodoo Hands",
            "winmsg": "±Foot: Using the powers of darkness and corruption, ~Players~ cheated their way to victory."
        }
    ],
    "lynchmsg": "±Foot: ~Player~ cheated and was disqualified!",
    "killmsg": "±Foot: ~Player~ (~Role~) was eliminated!",
    "killusermsg": "±Foot: You've been hit too many times. Sorry, but you're out!",
	"drawmsg": "±Foot: Sometimes life is a giant draw, just like this game. Sorry guys!",
	"variables": {
				"gun attack":{
                    "gun": {
					"hide": true, "command": [ "kill" ], "priority": 1,
                        "common": "Self",
                        "target": "AnyButTeam"
                    } },
				"paper attack":{
                    "paper": {
					"hide": true, "command": [ "convert", "dummy", "dummy2" ], "priority": 2,
                        "common": "Self",
                        "silent": true,
                        "silentConvert": true,
                        "target": "AnyButSelf",
						"newRole": "variable:paper damage",
                        "dummytargetmsg": "Another piece of Paper attacked you! You received 1 point of damage.",
                        "dummyusermsg": "Your target was Paper too! You dealt 1 point of damage to them.",
                        "dummy2targetmsg": "Paper wraps Rock! You received 2 points of damage.",
                        "dummy2usermsg": "You wrapped a Rock! You dealt 2 points of damage to them.",
						"convertfailmsg": "A pair of Scissors has deflected your attack!"
                    } },
				"paper damage": { "rwrock5": [ "rwrock7" ], "rwrock4": [ "rwrock6" ], "rwrock3": [ "rwrock5" ], "rwrock2": [ "rwrock4" ], "rwrock1": [ "rwrock3" ], "rwrock0": [ "rwrock2", "rwrock1", "rwrock0" ], "swrock5": [ "swrock7" ], "swrock4": [ "swrock6" ], "swrock3": [ "swrock5" ], "swrock2": [ "swrock4" ], "swrock1": [ "swrock3" ], "swrock0": [ "swrock2", "swrock1", "swrock0" ], "owrock5": [ "owrock7" ], "owrock4": [ "owrock6" ], "owrock3": [ "owrock5" ], "owrock2": [ "owrock4" ], "owrock1": [ "owrock3" ], "owrock0": [ "owrock2", "owrock1", "owrock0" ], "ywrock5": [ "ywrock7" ], "ywrock4": [ "ywrock6" ], "ywrock3": [ "ywrock5" ], "ywrock2": [ "ywrock4" ], "ywrock1": [ "ywrock3" ], "ywrock0": [ "ywrock2", "ywrock1", "ywrock0" ], "bcrock5": [ "bcrock7" ], "bcrock4": [ "bcrock6" ], "bcrock3": [ "bcrock5" ], "bcrock2": [ "bcrock4" ], "bcrock1": [ "bcrock3" ], "bcrock0": [ "bcrock2", "bcrock1", "bcrock0" ], "gcrock5": [ "gcrock7" ], "gcrock4": [ "gcrock6" ], "gcrock3": [ "gcrock5" ], "gcrock2": [ "gcrock4" ], "gcrock1": [ "gcrock3" ], "gcrock0": [ "gcrock2", "gcrock1", "gcrock0" ], "pcrock5": [ "pcrock7" ], "pcrock4": [ "pcrock6" ], "pcrock3": [ "pcrock5" ], "pcrock2": [ "pcrock4" ], "pcrock1": [ "pcrock3" ], "pcrock0": [ "pcrock2", "pcrock1", "pcrock0" ], "mcrock5": [ "mcrock7" ], "mcrock4": [ "mcrock6" ], "mcrock3": [ "mcrock5" ], "mcrock2": [ "mcrock4" ], "mcrock1": [ "mcrock3" ], "mcrock0": [ "mcrock2", "mcrock1", "mcrock0" ], "corock5": [ "corock7" ], "corock4": [ "corock6" ], "corock3": [ "corock5" ], "corock2": [ "corock4" ], "corock1": [ "corock3" ], "corock0": [ "corock2", "corock1", "corock0" ], "borock5": [ "borock7" ], "borock4": [ "borock6" ], "borock3": [ "borock5" ], "borock2": [ "borock4" ], "borock1": [ "borock3" ], "borock0": [ "borock2", "borock1", "borock0" ], "sorock5": [ "sorock7" ], "sorock4": [ "sorock6" ], "sorock3": [ "sorock5" ], "sorock2": [ "sorock4" ], "sorock1": [ "sorock3" ], "sorock0": [ "sorock2", "sorock1", "sorock0" ], "gorock5": [ "gorock7" ], "gorock4": [ "gorock6" ], "gorock3": [ "gorock5" ], "gorock2": [ "gorock4" ], "gorock1": [ "gorock3" ], "gorock0": [ "gorock2", "gorock1", "gorock0" ],
								  "vvgun5": [ "vvgun7" ], "vvgun4": [ "vvgun6" ], "vvgun3": [ "vvgun5" ], "vvgun2": [ "vvgun4" ], "vvgun1": [ "vvgun3" ], "vvgun0": [ "vvgun2", "vvgun1", "vvgun0" ],
								  "rwhand5": [ "rwhand7" ], "rwhand4": [ "rwhand6" ], "rwhand3": [ "rwhand5" ], "rwhand2": [ "rwhand4" ], "rwhand1": [ "rwhand3" ], "rwhand0": [ "rwhand2", "rwhand1", "rwhand0" ], "swhand5": [ "swhand7" ], "swhand4": [ "swhand6" ], "swhand3": [ "swhand5" ], "swhand2": [ "swhand4" ], "swhand1": [ "swhand3" ], "swhand0": [ "swhand2", "swhand1", "swhand0" ], "owhand5": [ "owhand7" ], "owhand4": [ "owhand6" ], "owhand3": [ "owhand5" ], "owhand2": [ "owhand4" ], "owhand1": [ "owhand3" ], "owhand0": [ "owhand2", "owhand1", "owhand0" ], "ywhand5": [ "ywhand7" ], "ywhand4": [ "ywhand6" ], "ywhand3": [ "ywhand5" ], "ywhand2": [ "ywhand4" ], "ywhand1": [ "ywhand3" ], "ywhand0": [ "ywhand2", "ywhand1", "ywhand0" ], "bchand5": [ "bchand7" ], "bchand4": [ "bchand6" ], "bchand3": [ "bchand5" ], "bchand2": [ "bchand4" ], "bchand1": [ "bchand3" ], "bchand0": [ "bchand2", "bchand1", "bchand0" ], "gchand5": [ "gchand7" ], "gchand4": [ "gchand6" ], "gchand3": [ "gchand5" ], "gchand2": [ "gchand4" ], "gchand1": [ "gchand3" ], "gchand0": [ "gchand2", "gchand1", "gchand0" ], "pchand5": [ "pchand7" ], "pchand4": [ "pchand6" ], "pchand3": [ "pchand5" ], "pchand2": [ "pchand4" ], "pchand1": [ "pchand3" ], "pchand0": [ "pchand2", "pchand1", "pchand0" ], "mchand5": [ "mchand7" ], "mchand4": [ "mchand6" ], "mchand3": [ "mchand5" ], "mchand2": [ "mchand4" ], "mchand1": [ "mchand3" ], "mchand0": [ "mchand2", "mchand1", "mchand0" ], "cohand5": [ "cohand7" ], "cohand4": [ "cohand6" ], "cohand3": [ "cohand5" ], "cohand2": [ "cohand4" ], "cohand1": [ "cohand3" ], "cohand0": [ "cohand2", "cohand1", "cohand0" ], "bohand5": [ "bohand7" ], "bohand4": [ "bohand6" ], "bohand3": [ "bohand5" ], "bohand2": [ "bohand4" ], "bohand1": [ "bohand3" ], "bohand0": [ "bohand2", "bohand1", "bohand0" ], "sohand5": [ "sohand7" ], "sohand4": [ "sohand6" ], "sohand3": [ "sohand5" ], "sohand2": [ "sohand4" ], "sohand1": [ "sohand3" ], "sohand0": [ "sohand2", "sohand1", "sohand0" ], "gohand5": [ "gohand7" ], "gohand4": [ "gohand6" ], "gohand3": [ "gohand5" ], "gohand2": [ "gohand4" ], "gohand1": [ "gohand3" ], "gohand0": [ "gohand2", "gohand1", "gohand0" ],
								  "vvhand5": [ "vvhand7", "vvhand7x" ], "vvhand4": [ "vvhand6", "vvhand6x" ], "vvhand3": [ "vvhand5", "vvhand5" ], "vvhand2": [ "vvhand4", "vvhand4x"], "vvhand1": [ "vvhand3", "vvhand3" ], "vvhand0": [ "vvhand2", "vvhand1", "vvhand0", "vvhand2x", "vvhand1x", "vvhand0x" ],
								  "rwpaper6": [ "rwpaper7" ], "rwpaper5": [ "rwpaper6" ], "rwpaper4": [ "rwpaper5" ], "rwpaper3": [ "rwpaper4" ], "rwpaper2": [ "rwpaper3" ], "rwpaper1": [ "rwpaper2"], "rwpaper0": [ "rwpaper1", "rwpaper0" ], "swpaper6": [ "swpaper7" ], "swpaper5": [ "swpaper6" ], "swpaper4": [ "swpaper5" ], "swpaper3": [ "swpaper4" ], "swpaper2": [ "swpaper3" ], "swpaper1": [ "swpaper2"], "swpaper0": [ "swpaper1", "swpaper0" ], "owpaper6": [ "owpaper7" ], "owpaper5": [ "owpaper6" ], "owpaper4": [ "owpaper5" ], "owpaper3": [ "owpaper4" ], "owpaper2": [ "owpaper3" ], "owpaper1": [ "owpaper2"], "owpaper0": [ "owpaper1", "owpaper0" ], "ywpaper6": [ "ywpaper7" ], "ywpaper5": [ "ywpaper6" ], "ywpaper4": [ "ywpaper5" ], "ywpaper3": [ "ywpaper4" ], "ywpaper2": [ "ywpaper3" ], "ywpaper1": [ "ywpaper2"], "ywpaper0": [ "ywpaper1", "ywpaper0" ], "bcpaper6": [ "bcpaper7" ], "bcpaper5": [ "bcpaper6" ], "bcpaper4": [ "bcpaper5" ], "bcpaper3": [ "bcpaper4" ], "bcpaper2": [ "bcpaper3" ], "bcpaper1": [ "bcpaper2"], "bcpaper0": [ "bcpaper1", "bcpaper0" ], "gcpaper6": [ "gcpaper7" ], "gcpaper5": [ "gcpaper6" ], "gcpaper4": [ "gcpaper5" ], "gcpaper3": [ "gcpaper4" ], "gcpaper2": [ "gcpaper3" ], "gcpaper1": [ "gcpaper2"], "gcpaper0": [ "gcpaper1", "gcpaper0" ], "pcpaper6": [ "pcpaper7" ], "pcpaper5": [ "pcpaper6" ], "pcpaper4": [ "pcpaper5" ], "pcpaper3": [ "pcpaper4" ], "pcpaper2": [ "pcpaper3" ], "pcpaper1": [ "pcpaper2"], "pcpaper0": [ "pcpaper1", "pcpaper0" ], "mcpaper6": [ "mcpaper7" ], "mcpaper5": [ "mcpaper6" ], "mcpaper4": [ "mcpaper5" ], "mcpaper3": [ "mcpaper4" ], "mcpaper2": [ "mcpaper3" ], "mcpaper1": [ "mcpaper2"], "mcpaper0": [ "mcpaper1", "mcpaper0" ], "copaper6": [ "copaper7" ], "copaper5": [ "copaper6" ], "copaper4": [ "copaper5" ], "copaper3": [ "copaper4" ], "copaper2": [ "copaper3" ], "copaper1": [ "copaper2"], "copaper0": [ "copaper1", "copaper0" ], "bopaper6": [ "bopaper7" ], "bopaper5": [ "bopaper6" ], "bopaper4": [ "bopaper5" ], "bopaper3": [ "bopaper4" ], "bopaper2": [ "bopaper3" ], "bopaper1": [ "bopaper2"], "bopaper0": [ "bopaper1", "bopaper0" ], "sopaper6": [ "sopaper7" ], "sopaper5": [ "sopaper6" ], "sopaper4": [ "sopaper5" ], "sopaper3": [ "sopaper4" ], "sopaper2": [ "sopaper3" ], "sopaper1": [ "sopaper2"], "sopaper0": [ "sopaper1", "sopaper0" ], "gopaper6": [ "gopaper7" ], "gopaper5": [ "gopaper6" ], "gopaper4": [ "gopaper5" ], "gopaper3": [ "gopaper4" ], "gopaper2": [ "gopaper3" ], "gopaper1": [ "gopaper2"], "gopaper0": [ "gopaper1", "gopaper0" ]
								},
				"scissors attack":{
                    "scissors": {
					"hide": true, "command": [ "convert", "dummy3", "dummy4" ], "priority": 2,
                        "common": "Self",
                        "silent": true,
                        "silentConvert": true,
                        "target": "AnyButSelf",
						"newRole": "variable:scissors damage",
                        "dummy3targetmsg": "Another pair of Scissors attacked you! You received 1 point of damage.",
                        "dummy3usermsg": "Your target was Scissors too! You dealt 1 point of damage to them.",
                        "dummy4targetmsg": "Scissors cuts Paper! You received 2 points of damage.",
                        "dummy4usermsg": "You cut a piece of Paper! You dealt 2 points of damage to them.",
						"convertfailmsg": "A Rock has deflected your attack!"
                    } },
				"scissors damage": { "rwpaper5": [ "rwpaper7" ], "rwpaper4": [ "rwpaper6" ], "rwpaper3": [ "rwpaper5" ], "rwpaper2": [ "rwpaper4" ], "rwpaper1": [ "rwpaper3" ], "rwpaper0": [ "rwpaper2", "rwpaper1", "rwpaper0" ], "swpaper5": [ "swpaper7" ], "swpaper4": [ "swpaper6" ], "swpaper3": [ "swpaper5" ], "swpaper2": [ "swpaper4" ], "swpaper1": [ "swpaper3" ], "swpaper0": [ "swpaper2", "swpaper1", "swpaper0" ], "owpaper5": [ "owpaper7" ], "owpaper4": [ "owpaper6" ], "owpaper3": [ "owpaper5" ], "owpaper2": [ "owpaper4" ], "owpaper1": [ "owpaper3" ], "owpaper0": [ "owpaper2", "owpaper1", "owpaper0" ], "ywpaper5": [ "ywpaper7" ], "ywpaper4": [ "ywpaper6" ], "ywpaper3": [ "ywpaper5" ], "ywpaper2": [ "ywpaper4" ], "ywpaper1": [ "ywpaper3" ], "ywpaper0": [ "ywpaper2", "ywpaper1", "ywpaper0" ], "bcpaper5": [ "bcpaper7" ], "bcpaper4": [ "bcpaper6" ], "bcpaper3": [ "bcpaper5" ], "bcpaper2": [ "bcpaper4" ], "bcpaper1": [ "bcpaper3" ], "bcpaper0": [ "bcpaper2", "bcpaper1", "bcpaper0" ], "gcpaper5": [ "gcpaper7" ], "gcpaper4": [ "gcpaper6" ], "gcpaper3": [ "gcpaper5" ], "gcpaper2": [ "gcpaper4" ], "gcpaper1": [ "gcpaper3" ], "gcpaper0": [ "gcpaper2", "gcpaper1", "gcpaper0" ], "pcpaper5": [ "pcpaper7" ], "pcpaper4": [ "pcpaper6" ], "pcpaper3": [ "pcpaper5" ], "pcpaper2": [ "pcpaper4" ], "pcpaper1": [ "pcpaper3" ], "pcpaper0": [ "pcpaper2", "pcpaper1", "pcpaper0" ], "mcpaper5": [ "mcpaper7" ], "mcpaper4": [ "mcpaper6" ], "mcpaper3": [ "mcpaper5" ], "mcpaper2": [ "mcpaper4" ], "mcpaper1": [ "mcpaper3" ], "mcpaper0": [ "mcpaper2", "mcpaper1", "mcpaper0" ], "copaper5": [ "copaper7" ], "copaper4": [ "copaper6" ], "copaper3": [ "copaper5" ], "copaper2": [ "copaper4" ], "copaper1": [ "copaper3" ], "copaper0": [ "copaper2", "copaper1", "copaper0" ], "bopaper5": [ "bopaper7" ], "bopaper4": [ "bopaper6" ], "bopaper3": [ "bopaper5" ], "bopaper2": [ "bopaper4" ], "bopaper1": [ "bopaper3" ], "bopaper0": [ "bopaper2", "bopaper1", "bopaper0" ], "sopaper5": [ "sopaper7" ], "sopaper4": [ "sopaper6" ], "sopaper3": [ "sopaper5" ], "sopaper2": [ "sopaper4" ], "sopaper1": [ "sopaper3" ], "sopaper0": [ "sopaper2", "sopaper1", "sopaper0" ], "gopaper5": [ "gopaper7" ], "gopaper4": [ "gopaper6" ], "gopaper3": [ "gopaper5" ], "gopaper2": [ "gopaper4" ], "gopaper1": [ "gopaper3" ], "gopaper0": [ "gopaper2", "gopaper1", "gopaper0" ],
								  "vvgun5": [ "vvgun7" ], "vvgun4": [ "vvgun6" ], "vvgun3": [ "vvgun5" ], "vvgun2": [ "vvgun4" ], "vvgun1": [ "vvgun3" ], "vvgun0": [ "vvgun2", "vvgun1", "vvgun0" ],
								  "rwhand5": [ "rwhand7" ], "rwhand4": [ "rwhand6" ], "rwhand3": [ "rwhand5" ], "rwhand2": [ "rwhand4" ], "rwhand1": [ "rwhand3" ], "rwhand0": [ "rwhand2", "rwhand1", "rwhand0" ], "swhand5": [ "swhand7" ], "swhand4": [ "swhand6" ], "swhand3": [ "swhand5" ], "swhand2": [ "swhand4" ], "swhand1": [ "swhand3" ], "swhand0": [ "swhand2", "swhand1", "swhand0" ], "owhand5": [ "owhand7" ], "owhand4": [ "owhand6" ], "owhand3": [ "owhand5" ], "owhand2": [ "owhand4" ], "owhand1": [ "owhand3" ], "owhand0": [ "owhand2", "owhand1", "owhand0" ], "ywhand5": [ "ywhand7" ], "ywhand4": [ "ywhand6" ], "ywhand3": [ "ywhand5" ], "ywhand2": [ "ywhand4" ], "ywhand1": [ "ywhand3" ], "ywhand0": [ "ywhand2", "ywhand1", "ywhand0" ], "bchand5": [ "bchand7" ], "bchand4": [ "bchand6" ], "bchand3": [ "bchand5" ], "bchand2": [ "bchand4" ], "bchand1": [ "bchand3" ], "bchand0": [ "bchand2", "bchand1", "bchand0" ], "gchand5": [ "gchand7" ], "gchand4": [ "gchand6" ], "gchand3": [ "gchand5" ], "gchand2": [ "gchand4" ], "gchand1": [ "gchand3" ], "gchand0": [ "gchand2", "gchand1", "gchand0" ], "pchand5": [ "pchand7" ], "pchand4": [ "pchand6" ], "pchand3": [ "pchand5" ], "pchand2": [ "pchand4" ], "pchand1": [ "pchand3" ], "pchand0": [ "pchand2", "pchand1", "pchand0" ], "mchand5": [ "mchand7" ], "mchand4": [ "mchand6" ], "mchand3": [ "mchand5" ], "mchand2": [ "mchand4" ], "mchand1": [ "mchand3" ], "mchand0": [ "mchand2", "mchand1", "mchand0" ], "cohand5": [ "cohand7" ], "cohand4": [ "cohand6" ], "cohand3": [ "cohand5" ], "cohand2": [ "cohand4" ], "cohand1": [ "cohand3" ], "cohand0": [ "cohand2", "cohand1", "cohand0" ], "bohand5": [ "bohand7" ], "bohand4": [ "bohand6" ], "bohand3": [ "bohand5" ], "bohand2": [ "bohand4" ], "bohand1": [ "bohand3" ], "bohand0": [ "bohand2", "bohand1", "bohand0" ], "sohand5": [ "sohand7" ], "sohand4": [ "sohand6" ], "sohand3": [ "sohand5" ], "sohand2": [ "sohand4" ], "sohand1": [ "sohand3" ], "sohand0": [ "sohand2", "sohand1", "sohand0" ], "gohand5": [ "gohand7" ], "gohand4": [ "gohand6" ], "gohand3": [ "gohand5" ], "gohand2": [ "gohand4" ], "gohand1": [ "gohand3" ], "gohand0": [ "gohand2", "gohand1", "gohand0" ],
								  "vvhand5": [ "vvhand7", "vvhand7x" ], "vvhand4": [ "vvhand6", "vvhand6x" ], "vvhand3": [ "vvhand5", "vvhand5" ], "vvhand2": [ "vvhand4", "vvhand4x"], "vvhand1": [ "vvhand3", "vvhand3" ], "vvhand0": [ "vvhand2", "vvhand1", "vvhand0", "vvhand2x", "vvhand1x", "vvhand0x" ],
								  "rwscissors6": [ "rwscissors7" ], "rwscissors5": [ "rwscissors6" ], "rwscissors4": [ "rwscissors5" ], "rwscissors3": [ "rwscissors4" ], "rwscissors2": [ "rwscissors3" ], "rwscissors1": [ "rwscissors2"], "rwscissors0": [ "rwscissors1", "rwscissors0" ], "swscissors6": [ "swscissors7" ], "swscissors5": [ "swscissors6" ], "swscissors4": [ "swscissors5" ], "swscissors3": [ "swscissors4" ], "swscissors2": [ "swscissors3" ], "swscissors1": [ "swscissors2"], "swscissors0": [ "swscissors1", "swscissors0" ], "owscissors6": [ "owscissors7" ], "owscissors5": [ "owscissors6" ], "owscissors4": [ "owscissors5" ], "owscissors3": [ "owscissors4" ], "owscissors2": [ "owscissors3" ], "owscissors1": [ "owscissors2"], "owscissors0": [ "owscissors1", "owscissors0" ], "ywscissors6": [ "ywscissors7" ], "ywscissors5": [ "ywscissors6" ], "ywscissors4": [ "ywscissors5" ], "ywscissors3": [ "ywscissors4" ], "ywscissors2": [ "ywscissors3" ], "ywscissors1": [ "ywscissors2"], "ywscissors0": [ "ywscissors1", "ywscissors0" ], "bcscissors6": [ "bcscissors7" ], "bcscissors5": [ "bcscissors6" ], "bcscissors4": [ "bcscissors5" ], "bcscissors3": [ "bcscissors4" ], "bcscissors2": [ "bcscissors3" ], "bcscissors1": [ "bcscissors2"], "bcscissors0": [ "bcscissors1", "bcscissors0" ], "gcscissors6": [ "gcscissors7" ], "gcscissors5": [ "gcscissors6" ], "gcscissors4": [ "gcscissors5" ], "gcscissors3": [ "gcscissors4" ], "gcscissors2": [ "gcscissors3" ], "gcscissors1": [ "gcscissors2"], "gcscissors0": [ "gcscissors1", "gcscissors0" ], "pcscissors6": [ "pcscissors7" ], "pcscissors5": [ "pcscissors6" ], "pcscissors4": [ "pcscissors5" ], "pcscissors3": [ "pcscissors4" ], "pcscissors2": [ "pcscissors3" ], "pcscissors1": [ "pcscissors2"], "pcscissors0": [ "pcscissors1", "pcscissors0" ], "mcscissors6": [ "mcscissors7" ], "mcscissors5": [ "mcscissors6" ], "mcscissors4": [ "mcscissors5" ], "mcscissors3": [ "mcscissors4" ], "mcscissors2": [ "mcscissors3" ], "mcscissors1": [ "mcscissors2"], "mcscissors0": [ "mcscissors1", "mcscissors0" ], "coscissors6": [ "coscissors7" ], "coscissors5": [ "coscissors6" ], "coscissors4": [ "coscissors5" ], "coscissors3": [ "coscissors4" ], "coscissors2": [ "coscissors3" ], "coscissors1": [ "coscissors2"], "coscissors0": [ "coscissors1", "coscissors0" ], "boscissors6": [ "boscissors7" ], "boscissors5": [ "boscissors6" ], "boscissors4": [ "boscissors5" ], "boscissors3": [ "boscissors4" ], "boscissors2": [ "boscissors3" ], "boscissors1": [ "boscissors2"], "boscissors0": [ "boscissors1", "boscissors0" ], "soscissors6": [ "soscissors7" ], "soscissors5": [ "soscissors6" ], "soscissors4": [ "soscissors5" ], "soscissors3": [ "soscissors4" ], "soscissors2": [ "soscissors3" ], "soscissors1": [ "soscissors2"], "soscissors0": [ "soscissors1", "soscissors0" ], "goscissors6": [ "goscissors7" ], "goscissors5": [ "goscissors6" ], "goscissors4": [ "goscissors5" ], "goscissors3": [ "goscissors4" ], "goscissors2": [ "goscissors3" ], "goscissors1": [ "goscissors2"], "goscissors0": [ "goscissors1", "goscissors0" ]
								},
				"rock attack":{
                    "rock": {
					"hide": true, "command": [ "convert", "dummy5", "dummy6" ], "priority": 2,
                        "common": "Self",
                        "silent": true,
                        "silentConvert": true,
                        "target": "AnyButSelf",
						"newRole": "variable:rock damage",
                        "dummy5targetmsg": "Another Rock attacked you! You received 1 point of damage.",
                        "dummy5usermsg": "Your target was a Rock too! You dealt 1 point of damage to them.",
                        "dummy6targetmsg": "Rock smashes Scissors! You received 2 points of damage.",
                        "dummy6usermsg": "You smashed a pair of Scissors! You dealt 2 points of damage to them.",
						"convertfailmsg": "A piece of Paper has deflected your attack!"
                    } },
				"rock damage": { "rwscissors5": [ "rwscissors7" ], "rwscissors4": [ "rwscissors6" ], "rwscissors3": [ "rwscissors5" ], "rwscissors2": [ "rwscissors4" ], "rwscissors1": [ "rwscissors3" ], "rwscissors0": [ "rwscissors2", "rwscissors1", "rwscissors0" ], "swscissors5": [ "swscissors7" ], "swscissors4": [ "swscissors6" ], "swscissors3": [ "swscissors5" ], "swscissors2": [ "swscissors4" ], "swscissors1": [ "swscissors3" ], "swscissors0": [ "swscissors2", "swscissors1", "swscissors0" ], "owscissors5": [ "owscissors7" ], "owscissors4": [ "owscissors6" ], "owscissors3": [ "owscissors5" ], "owscissors2": [ "owscissors4" ], "owscissors1": [ "owscissors3" ], "owscissors0": [ "owscissors2", "owscissors1", "owscissors0" ], "ywscissors5": [ "ywscissors7" ], "ywscissors4": [ "ywscissors6" ], "ywscissors3": [ "ywscissors5" ], "ywscissors2": [ "ywscissors4" ], "ywscissors1": [ "ywscissors3" ], "ywscissors0": [ "ywscissors2", "ywscissors1", "ywscissors0" ], "bcscissors5": [ "bcscissors7" ], "bcscissors4": [ "bcscissors6" ], "bcscissors3": [ "bcscissors5" ], "bcscissors2": [ "bcscissors4" ], "bcscissors1": [ "bcscissors3" ], "bcscissors0": [ "bcscissors2", "bcscissors1", "bcscissors0" ], "gcscissors5": [ "gcscissors7" ], "gcscissors4": [ "gcscissors6" ], "gcscissors3": [ "gcscissors5" ], "gcscissors2": [ "gcscissors4" ], "gcscissors1": [ "gcscissors3" ], "gcscissors0": [ "gcscissors2", "gcscissors1", "gcscissors0" ], "pcscissors5": [ "pcscissors7" ], "pcscissors4": [ "pcscissors6" ], "pcscissors3": [ "pcscissors5" ], "pcscissors2": [ "pcscissors4" ], "pcscissors1": [ "pcscissors3" ], "pcscissors0": [ "pcscissors2", "pcscissors1", "pcscissors0" ], "mcscissors5": [ "mcscissors7" ], "mcscissors4": [ "mcscissors6" ], "mcscissors3": [ "mcscissors5" ], "mcscissors2": [ "mcscissors4" ], "mcscissors1": [ "mcscissors3" ], "mcscissors0": [ "mcscissors2", "mcscissors1", "mcscissors0" ], "coscissors5": [ "coscissors7" ], "coscissors4": [ "coscissors6" ], "coscissors3": [ "coscissors5" ], "coscissors2": [ "coscissors4" ], "coscissors1": [ "coscissors3" ], "coscissors0": [ "coscissors2", "coscissors1", "coscissors0" ], "boscissors5": [ "boscissors7" ], "boscissors4": [ "boscissors6" ], "boscissors3": [ "boscissors5" ], "boscissors2": [ "boscissors4" ], "boscissors1": [ "boscissors3" ], "boscissors0": [ "boscissors2", "boscissors1", "boscissors0" ], "soscissors5": [ "soscissors7" ], "soscissors4": [ "soscissors6" ], "soscissors3": [ "soscissors5" ], "soscissors2": [ "soscissors4" ], "soscissors1": [ "soscissors3" ], "soscissors0": [ "soscissors2", "soscissors1", "soscissors0" ], "goscissors5": [ "goscissors7" ], "goscissors4": [ "goscissors6" ], "goscissors3": [ "goscissors5" ], "goscissors2": [ "goscissors4" ], "goscissors1": [ "goscissors3" ], "goscissors0": [ "goscissors2", "goscissors1", "goscissors0" ],
								  "vvgun5": [ "vvgun7" ], "vvgun4": [ "vvgun6" ], "vvgun3": [ "vvgun5" ], "vvgun2": [ "vvgun4" ], "vvgun1": [ "vvgun3" ], "vvgun0": [ "vvgun2", "vvgun1", "vvgun0" ],
								  "rwhand5": [ "rwhand7" ], "rwhand4": [ "rwhand6" ], "rwhand3": [ "rwhand5" ], "rwhand2": [ "rwhand4" ], "rwhand1": [ "rwhand3" ], "rwhand0": [ "rwhand2", "rwhand1", "rwhand0" ], "swhand5": [ "swhand7" ], "swhand4": [ "swhand6" ], "swhand3": [ "swhand5" ], "swhand2": [ "swhand4" ], "swhand1": [ "swhand3" ], "swhand0": [ "swhand2", "swhand1", "swhand0" ], "owhand5": [ "owhand7" ], "owhand4": [ "owhand6" ], "owhand3": [ "owhand5" ], "owhand2": [ "owhand4" ], "owhand1": [ "owhand3" ], "owhand0": [ "owhand2", "owhand1", "owhand0" ], "ywhand5": [ "ywhand7" ], "ywhand4": [ "ywhand6" ], "ywhand3": [ "ywhand5" ], "ywhand2": [ "ywhand4" ], "ywhand1": [ "ywhand3" ], "ywhand0": [ "ywhand2", "ywhand1", "ywhand0" ], "bchand5": [ "bchand7" ], "bchand4": [ "bchand6" ], "bchand3": [ "bchand5" ], "bchand2": [ "bchand4" ], "bchand1": [ "bchand3" ], "bchand0": [ "bchand2", "bchand1", "bchand0" ], "gchand5": [ "gchand7" ], "gchand4": [ "gchand6" ], "gchand3": [ "gchand5" ], "gchand2": [ "gchand4" ], "gchand1": [ "gchand3" ], "gchand0": [ "gchand2", "gchand1", "gchand0" ], "pchand5": [ "pchand7" ], "pchand4": [ "pchand6" ], "pchand3": [ "pchand5" ], "pchand2": [ "pchand4" ], "pchand1": [ "pchand3" ], "pchand0": [ "pchand2", "pchand1", "pchand0" ], "mchand5": [ "mchand7" ], "mchand4": [ "mchand6" ], "mchand3": [ "mchand5" ], "mchand2": [ "mchand4" ], "mchand1": [ "mchand3" ], "mchand0": [ "mchand2", "mchand1", "mchand0" ], "cohand5": [ "cohand7" ], "cohand4": [ "cohand6" ], "cohand3": [ "cohand5" ], "cohand2": [ "cohand4" ], "cohand1": [ "cohand3" ], "cohand0": [ "cohand2", "cohand1", "cohand0" ], "bohand5": [ "bohand7" ], "bohand4": [ "bohand6" ], "bohand3": [ "bohand5" ], "bohand2": [ "bohand4" ], "bohand1": [ "bohand3" ], "bohand0": [ "bohand2", "bohand1", "bohand0" ], "sohand5": [ "sohand7" ], "sohand4": [ "sohand6" ], "sohand3": [ "sohand5" ], "sohand2": [ "sohand4" ], "sohand1": [ "sohand3" ], "sohand0": [ "sohand2", "sohand1", "sohand0" ], "gohand5": [ "gohand7" ], "gohand4": [ "gohand6" ], "gohand3": [ "gohand5" ], "gohand2": [ "gohand4" ], "gohand1": [ "gohand3" ], "gohand0": [ "gohand2", "gohand1", "gohand0" ],
								  "vvhand5": [ "vvhand7", "vvhand7x" ], "vvhand4": [ "vvhand6", "vvhand6x" ], "vvhand3": [ "vvhand5", "vvhand5" ], "vvhand2": [ "vvhand4", "vvhand4x"], "vvhand1": [ "vvhand3", "vvhand3" ], "vvhand0": [ "vvhand2", "vvhand1", "vvhand0", "vvhand2x", "vvhand1x", "vvhand0x" ],
								  "rwrock6": [ "rwrock7" ], "rwrock5": [ "rwrock6" ], "rwrock4": [ "rwrock5" ], "rwrock3": [ "rwrock4" ], "rwrock2": [ "rwrock3" ], "rwrock1": [ "rwrock2"], "rwrock0": [ "rwrock1", "rwrock0" ], "swrock6": [ "swrock7" ], "swrock5": [ "swrock6" ], "swrock4": [ "swrock5" ], "swrock3": [ "swrock4" ], "swrock2": [ "swrock3" ], "swrock1": [ "swrock2"], "swrock0": [ "swrock1", "swrock0" ], "owrock6": [ "owrock7" ], "owrock5": [ "owrock6" ], "owrock4": [ "owrock5" ], "owrock3": [ "owrock4" ], "owrock2": [ "owrock3" ], "owrock1": [ "owrock2"], "owrock0": [ "owrock1", "owrock0" ], "ywrock6": [ "ywrock7" ], "ywrock5": [ "ywrock6" ], "ywrock4": [ "ywrock5" ], "ywrock3": [ "ywrock4" ], "ywrock2": [ "ywrock3" ], "ywrock1": [ "ywrock2"], "ywrock0": [ "ywrock1", "ywrock0" ], "bcrock6": [ "bcrock7" ], "bcrock5": [ "bcrock6" ], "bcrock4": [ "bcrock5" ], "bcrock3": [ "bcrock4" ], "bcrock2": [ "bcrock3" ], "bcrock1": [ "bcrock2"], "bcrock0": [ "bcrock1", "bcrock0" ], "gcrock6": [ "gcrock7" ], "gcrock5": [ "gcrock6" ], "gcrock4": [ "gcrock5" ], "gcrock3": [ "gcrock4" ], "gcrock2": [ "gcrock3" ], "gcrock1": [ "gcrock2"], "gcrock0": [ "gcrock1", "gcrock0" ], "pcrock6": [ "pcrock7" ], "pcrock5": [ "pcrock6" ], "pcrock4": [ "pcrock5" ], "pcrock3": [ "pcrock4" ], "pcrock2": [ "pcrock3" ], "pcrock1": [ "pcrock2"], "pcrock0": [ "pcrock1", "pcrock0" ], "mcrock6": [ "mcrock7" ], "mcrock5": [ "mcrock6" ], "mcrock4": [ "mcrock5" ], "mcrock3": [ "mcrock4" ], "mcrock2": [ "mcrock3" ], "mcrock1": [ "mcrock2"], "mcrock0": [ "mcrock1", "mcrock0" ], "corock6": [ "corock7" ], "corock5": [ "corock6" ], "corock4": [ "corock5" ], "corock3": [ "corock4" ], "corock2": [ "corock3" ], "corock1": [ "corock2"], "corock0": [ "corock1", "corock0" ], "borock6": [ "borock7" ], "borock5": [ "borock6" ], "borock4": [ "borock5" ], "borock3": [ "borock4" ], "borock2": [ "borock3" ], "borock1": [ "borock2"], "borock0": [ "borock1", "borock0" ], "sorock6": [ "sorock7" ], "sorock5": [ "sorock6" ], "sorock4": [ "sorock5" ], "sorock3": [ "sorock4" ], "sorock2": [ "sorock3" ], "sorock1": [ "sorock2"], "sorock0": [ "sorock1", "sorock0" ], "gorock6": [ "gorock7" ], "gorock5": [ "gorock6" ], "gorock4": [ "gorock5" ], "gorock3": [ "gorock4" ], "gorock2": [ "gorock3" ], "gorock1": [ "gorock2"], "gorock0": [ "gorock1", "gorock0" ]
								},
				"team rswarm": [
								"rwhand0", "rwhand1", "rwhand2", "rwhand3", "rwhand4", "rwhand5", "rwhand6", "rwhand7", "rwscissors0", "rwscissors1", "rwscissors2", "rwscissors3", "rwscissors4", "rwscissors5", "rwscissors6", "rwscissors7", "rwpaper0", "rwpaper1", "rwpaper2", "rwpaper3", "rwpaper4", "rwpaper5", "rwpaper6", "rwpaper7", "rwrock0", "rwrock1", "rwrock2", "rwrock3", "rwrock4", "rwrock5", "rwrock6", "rwrock7",
								"swhand0", "swhand1", "swhand2", "swhand3", "swhand4", "swhand5", "swhand6", "swhand7", "swscissors0", "swscissors1", "swscissors2", "swscissors3", "swscissors4", "swscissors5", "swscissors6", "swscissors7", "swpaper0", "swpaper1", "swpaper2", "swpaper3", "swpaper4", "swpaper5", "swpaper6", "swpaper7", "swrock0", "swrock1", "swrock2", "swrock3", "swrock4", "swrock5", "swrock6", "swrock7"
							   ],
				"team oywarm": [
								"owhand0", "owhand1", "owhand2", "owhand3", "owhand4", "owhand5", "owhand6", "owhand7", "owscissors0", "owscissors1", "owscissors2", "owscissors3", "owscissors4", "owscissors5", "owscissors6", "owscissors7", "owpaper0", "owpaper1", "owpaper2", "owpaper3", "owpaper4", "owpaper5", "owpaper6", "owpaper7", "owrock0", "owrock1", "owrock2", "owrock3", "owrock4", "owrock5", "owrock6", "owrock7",
								"ywhand0", "ywhand1", "ywhand2", "ywhand3", "ywhand4", "ywhand5", "ywhand6", "ywhand7", "ywscissors0", "ywscissors1", "ywscissors2", "ywscissors3", "ywscissors4", "ywscissors5", "ywscissors6", "ywscissors7", "ywpaper0", "ywpaper1", "ywpaper2", "ywpaper3", "ywpaper4", "ywpaper5", "ywpaper6", "ywpaper7", "ywrock0", "ywrock1", "ywrock2", "ywrock3", "ywrock4", "ywrock5", "ywrock6", "ywrock7"
							   ],
				"team bgcold": [
								"bchand0", "bchand1", "bchand2", "bchand3", "bchand4", "bchand5", "bchand6", "bchand7", "bcscissors0", "bcscissors1", "bcscissors2", "bcscissors3", "bcscissors4", "bcscissors5", "bcscissors6", "bcscissors7", "bcpaper0", "bcpaper1", "bcpaper2", "bcpaper3", "bcpaper4", "bcpaper5", "bcpaper6", "bcpaper7", "bcrock0", "bcrock1", "bcrock2", "bcrock3", "bcrock4", "bcrock5", "bcrock6", "bcrock7",
								"gchand0", "gchand1", "gchand2", "gchand3", "gchand4", "gchand5", "gchand6", "gchand7", "gcscissors0", "gcscissors1", "gcscissors2", "gcscissors3", "gcscissors4", "gcscissors5", "gcscissors6", "gcscissors7", "gcpaper0", "gcpaper1", "gcpaper2", "gcpaper3", "gcpaper4", "gcpaper5", "gcpaper6", "gcpaper7", "gcrock0", "gcrock1", "gcrock2", "gcrock3", "gcrock4", "gcrock5", "gcrock6", "gcrock7"
							   ],
				"team mpcold": [
								"mchand0", "mchand1", "mchand2", "mchand3", "mchand4", "mchand5", "mchand6", "mchand7", "mcscissors0", "mcscissors1", "mcscissors2", "mcscissors3", "mcscissors4", "mcscissors5", "mcscissors6", "mcscissors7", "mcpaper0", "mcpaper1", "mcpaper2", "mcpaper3", "mcpaper4", "mcpaper5", "mcpaper6", "mcpaper7", "mcrock0", "mcrock1", "mcrock2", "mcrock3", "mcrock4", "mcrock5", "mcrock6", "mcrock7",
								"pchand0", "pchand1", "pchand2", "pchand3", "pchand4", "pchand5", "pchand6", "pchand7", "pcscissors0", "pcscissors1", "pcscissors2", "pcscissors3", "pcscissors4", "pcscissors5", "pcscissors6", "pcscissors7", "pcpaper0", "pcpaper1", "pcpaper2", "pcpaper3", "pcpaper4", "pcpaper5", "pcpaper6", "pcpaper7", "pcrock0", "pcrock1", "pcrock2", "pcrock3", "pcrock4", "pcrock5", "pcrock6", "pcrock7"
							   ],
				"team bcoddball": [
								"bohand0", "bohand1", "bohand2", "bohand3", "bohand4", "bohand5", "bohand6", "bohand7", "boscissors0", "boscissors1", "boscissors2", "boscissors3", "boscissors4", "boscissors5", "boscissors6", "boscissors7", "bopaper0", "bopaper1", "bopaper2", "bopaper3", "bopaper4", "bopaper5", "bopaper6", "bopaper7", "borock0", "borock1", "borock2", "borock3", "borock4", "borock5", "borock6", "borock7",
								"cohand0", "cohand1", "cohand2", "cohand3", "cohand4", "cohand5", "cohand6", "cohand7", "coscissors0", "coscissors1", "coscissors2", "coscissors3", "coscissors4", "coscissors5", "coscissors6", "coscissors7", "copaper0", "copaper1", "copaper2", "copaper3", "copaper4", "copaper5", "copaper6", "copaper7", "corock0", "corock1", "corock2", "corock3", "corock4", "corock5", "corock6", "corock7"
							   ],
				"team gsoddball": [
								"gohand0", "gohand1", "gohand2", "gohand3", "gohand4", "gohand5", "gohand6", "gohand7", "goscissors0", "goscissors1", "goscissors2", "goscissors3", "goscissors4", "goscissors5", "goscissors6", "goscissors7", "gopaper0", "gopaper1", "gopaper2", "gopaper3", "gopaper4", "gopaper5", "gopaper6", "gopaper7", "gorock0", "gorock1", "gorock2", "gorock3", "gorock4", "gorock5", "gorock6", "gorock7",
								"sohand0", "sohand1", "sohand2", "sohand3", "sohand4", "sohand5", "sohand6", "sohand7", "soscissors0", "soscissors1", "soscissors2", "soscissors3", "soscissors4", "soscissors5", "soscissors6", "soscissors7", "sopaper0", "sopaper1", "sopaper2", "sopaper3", "sopaper4", "sopaper5", "sopaper6", "sopaper7", "sorock0", "sorock1", "sorock2", "sorock3", "sorock4", "sorock5", "sorock6", "sorock7"
							   ],
				"death msg": "You lost all your HP and died!",
				"rwhand help": "Infused with the power of fire, you are the Red Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Scarlet Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"swhand help": "Infused with the power of pure rage, you are the Scarlet Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Red Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"ywhand help": "Infused with the power of happiness and joy, you are the Yellow Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Orange Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This will also apply to people that hit you. Good luck!",
				"owhand help": "Infused with the power of pure energy, you are the Orange Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Yellow Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"bchand help": "Infused with the power of water, you are the Blue Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Green Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"gchand help": "Infused with the power of the forest, you are the Green Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Blue Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"pchand help": "Infused with honor and bravery, you are the Purple Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Magenta Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"mchand help": "Infused with the kindness of children worldwide, you are the Magenta Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Purple Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"cohand help": "Infused with the power of the skies, you are the Cyan Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Brown Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"bohand help": "Infused with the power of the land, you are the Brown Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Cyan Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"sohand help": "Infused with the power of style and class, you are the Silver Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Gold Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"gohand help": "Infused with the power of flash and wealth, you are the Gold Hand! It is your job to take out and remove all the other Hands that aren't on your team to become the Rock-Paper-Scissors champion! While you're on a team of 4, you're closest to the Silver Hand so you only know that hand. During the night, you may attack using /rock, /paper, or /scissors. This will transform you to that role for the night. If you get a good hit, like Scissors on Paper, the target loses 2HP whereas if you make a bad hit, like Rock on Paper, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Good luck!",
				"rwhand info": "Knows Scarlet Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Warm Colours.",
				"swhand info": "Knows Red Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Warm Colours.",
				"ywhand info": "Knows Orange Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Warm Colours.",
				"owhand info": "Knows Yellow Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Warm Colours.",
				"bchand info": "Knows Green Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Cold Colours.",
				"gchand info": "Knows Blue Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Cold Colours.",
				"pchand info": "Knows Magenta Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Cold Colours.",
				"mchand info": "Knows Purple Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Cold Colours.",
				"cohand info": "Knows Brown Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Oddball Colours.",
				"bohand info": "Knows Cyan Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Oddball Colours.",
				"sohand info": "Knows Gold Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Oddball Colours.",
				"gohand info": "Knows Silver Hand. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Oddball Colours.",
				"hand info": "Starts with 7HP. Hand can decides to be a /rock, a pair of /scissors or a piece of /paper until the end of the night and to deal 2 damages with their new role if their target is weak to them. If they don't transform during the night, they will be weak to any attack. Sided with their own colour.",
				"scissors help": "",
				"scissors info": "",
				"rock help": "",
				"rock info": "",
				"paper help": "",
				"paper info": "",
				"vvhand help": "Infused with everything dark and evil, you are the Voodo Hand! These silly hands keep arguing about who is best at Rock-Paper-Scissors when you've been the king for ages. During the night, you may use one of two actions. /gun will instantly kill the target whereas /shield will make you evade any hits. The only downside to you is that you take 2 points of damage regardless of what hits you, so you need to be careful. Also, you cannot use /gun back-to-back nor can you use /shield back-to-back, but best of luck to you. ",
				"vvhand info": "Can use /Gun (instakill) or /Shield (protect himself like if they are resistent to that type of attack) during the night but both of them needs to wait 2 turns before it can be used again. Recieves 2 points of damage as if weak to every type. Sided with Voodoo Hands.",
				"gun help": "",
				"gun info": "",
				"shield help": "",
				"shield info": ""
			 },
    "roles": [
        {   "role": "rwhand0",
            "translation": "Red Hand",
			"help": "variable:rwhand help",
            "info": "variable:rwhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand1",
            "translation": "Red Hand [1]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand2",
            "translation": "Red Hand [2]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand3",
            "translation": "Red Hand [3]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand4",
            "translation": "Red Hand [4]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand5",
            "translation": "Red Hand [5]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand6",
            "translation": "Red Hand [6]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand7",
            "translation": "Red Hand [7]",
			"hide": true,
			"help": "variable:rwhand help",
            "info": "variable:rwhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwpaper0",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper1",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper2",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper3",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper4",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper5",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper6",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper7",
            "translation": "Red Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwscissors0",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors1",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors2",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors3",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors4",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors5",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors6",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors7",
            "translation": "Red Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwrock0",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock1",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock2",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock3",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock4",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock5",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock6",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock7",
            "translation": "Red Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "rwhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swhand0",
            "translation": "Scarlet Hand",
			"help": "variable:swhand help",
            "info": "variable:swhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand1",
            "translation": "Scarlet Hand [1]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand2",
            "translation": "Scarlet Hand [2]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand3",
            "translation": "Scarlet Hand [3]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand4",
            "translation": "Scarlet Hand [4]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand5",
            "translation": "Scarlet Hand [5]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand6",
            "translation": "Scarlet Hand [6]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand7",
            "translation": "Scarlet Hand [7]",
			"help": "variable:swhand help",
			"hide": true,
            "info": "variable:swhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team rswarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swpaper0",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper1",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper2",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper3",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper4",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper5",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper6",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper7",
            "translation": "Scarlet Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swscissors0",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors1",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors2",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors3",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors4",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors5",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors6",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors7",
            "translation": "Scarlet Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swrock0",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock1",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock2",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock3",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock4",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock5",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock6",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock7",
            "translation": "Scarlet Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "swhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywhand0",
            "translation": "Yellow Hand",
			"help": "variable:ywhand help",
            "info": "variable:ywhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand1",
            "translation": "Yellow Hand [1]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand2",
            "translation": "Yellow Hand [2]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand3",
            "translation": "Yellow Hand [3]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand4",
            "translation": "Yellow Hand [4]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand5",
            "translation": "Yellow Hand [5]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand6",
            "translation": "Yellow Hand [6]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand7",
            "translation": "Yellow Hand [7]",
			"help": "variable:ywhand help",
			"hide": true,
            "info": "variable:ywhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywpaper0",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper1",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper2",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper3",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper4",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper5",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper6",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper7",
            "translation": "Yellow Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywscissors0",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors1",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors2",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors3",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors4",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors5",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors6",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors7",
            "translation": "Yellow Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywrock0",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock1",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock2",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock3",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock4",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock5",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock6",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock7",
            "translation": "Yellow Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "ywhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owhand0",
            "translation": "Orange Hand",
			"help": "variable:owhand help",
            "info": "variable:owhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand1",
            "translation": "Orange Hand [1]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand2",
            "translation": "Orange Hand [2]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand3",
            "translation": "Orange Hand [3]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand4",
            "translation": "Orange Hand [4]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand5",
            "translation": "Orange Hand [5]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand6",
            "translation": "Orange Hand [6]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand7",
            "translation": "Orange Hand [7]",
			"help": "variable:owhand help",
			"hide": true,
            "info": "variable:owhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team oywarm" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owpaper0",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper1",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper2",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper3",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper4",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper5",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper6",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper7",
            "translation": "Orange Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owscissors0",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors1",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors2",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors3",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors4",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors5",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors6",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors7",
            "translation": "Orange Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owrock0",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock1",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock2",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock3",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock4",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock5",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock6",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock7",
            "translation": "Orange Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "owhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pchand0",
            "translation": "Purple Hand",
			"help": "variable:pchand help",
            "info": "variable:pchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand1",
            "translation": "Purple Hand [1]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand2",
            "translation": "Purple Hand [2]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand3",
            "translation": "Purple Hand [3]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand4",
            "translation": "Purple Hand [4]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand5",
            "translation": "Purple Hand [5]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand6",
            "translation": "Purple Hand [6]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand7",
            "translation": "Purple Hand [7]",
			"help": "variable:pchand help",
			"hide": true,
            "info": "variable:pchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pcpaper0",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper1",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper2",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper3",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper4",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper5",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper6",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper7",
            "translation": "Purple Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcscissors0",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors1",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors2",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors3",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors4",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors5",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors6",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors7",
            "translation": "Purple Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcrock0",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock1",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock2",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock3",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock4",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock5",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock6",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock7",
            "translation": "Purple Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "pchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mchand0",
            "translation": "Magenta Hand",
			"help": "variable:mchand help",
            "info": "variable:mchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand1",
            "translation": "Magenta Hand [1]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand2",
            "translation": "Magenta Hand [2]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand3",
            "translation": "Magenta Hand [3]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand4",
            "translation": "Magenta Hand [4]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand5",
            "translation": "Magenta Hand [5]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand6",
            "translation": "Magenta Hand [6]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand7",
            "translation": "Magenta Hand [7]",
			"help": "variable:mchand help",
			"hide": true,
            "info": "variable:mchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team mpcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mcpaper0",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper1",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper2",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper3",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper4",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper5",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper6",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper7",
            "translation": "Magenta Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcscissors0",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors1",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors2",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors3",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors4",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors5",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors6",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors7",
            "translation": "Magenta Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcrock0",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock1",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock2",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock3",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock4",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock5",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock6",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock7",
            "translation": "Magenta Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "mchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bchand0",
            "translation": "Blue Hand",
			"help": "variable:bchand help",
            "info": "variable:bchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand1",
            "translation": "Blue Hand [1]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand2",
            "translation": "Blue Hand [2]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand3",
            "translation": "Blue Hand [3]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand4",
            "translation": "Blue Hand [4]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand5",
            "translation": "Blue Hand [5]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand6",
            "translation": "Blue Hand [6]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand7",
            "translation": "Blue Hand [7]",
			"help": "variable:bchand help",
			"hide": true,
            "info": "variable:bchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bcpaper0",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper1",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper2",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper3",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper4",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper5",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper6",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper7",
            "translation": "Blue Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcscissors0",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors1",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors2",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors3",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors4",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors5",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors6",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors7",
            "translation": "Blue Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcrock0",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock1",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock2",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock3",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock4",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock5",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock6",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock7",
            "translation": "Blue Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gchand0",
            "translation": "Green Hand",
			"help": "variable:gchand help",
            "info": "variable:gchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand1",
            "translation": "Green Hand [1]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand2",
            "translation": "Green Hand [2]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand3",
            "translation": "Green Hand [3]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand4",
            "translation": "Green Hand [4]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand5",
            "translation": "Green Hand [5]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand6",
            "translation": "Green Hand [6]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand7",
            "translation": "Green Hand [7]",
			"help": "variable:gchand help",
			"hide": true,
            "info": "variable:gchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bgcold" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gcpaper0",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper1",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper2",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper3",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper4",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper5",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper6",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper7",
            "translation": "Green Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcscissors0",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors1",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors2",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors3",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors4",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors5",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors6",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors7",
            "translation": "Green Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcrock0",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock1",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock2",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock3",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock4",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock5",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock6",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock7",
            "translation": "Green Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "cohand0",
            "translation": "Cyan Hand",
			"help": "variable:cohand help",
            "info": "variable:cohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand1",
            "translation": "Cyan Hand [1]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand2",
            "translation": "Cyan Hand [2]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand3",
            "translation": "Cyan Hand [3]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand4",
            "translation": "Cyan Hand [4]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand5",
            "translation": "Cyan Hand [5]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand6",
            "translation": "Cyan Hand [6]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand7",
            "translation": "Cyan Hand [7]",
			"help": "variable:cohand help",
			"hide": true,
            "info": "variable:cohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "copaper0",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper1",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper2",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper3",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper4",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper5",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper6",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper7",
            "translation": "Cyan Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "coscissors0",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors1",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors2",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors3",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors4",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors5",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors6",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors7",
            "translation": "Cyan Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "corock0",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock1",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock2",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock3",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock4",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock5",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock6",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock7",
            "translation": "Cyan Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "cohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bohand0",
            "translation": "Brown Hand",
			"help": "variable:bohand help",
            "info": "variable:bohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand1",
            "translation": "Brown Hand [1]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand2",
            "translation": "Brown Hand [2]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand3",
            "translation": "Brown Hand [3]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand4",
            "translation": "Brown Hand [4]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand5",
            "translation": "Brown Hand [5]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand6",
            "translation": "Brown Hand [6]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand7",
            "translation": "Brown Hand [7]",
			"help": "variable:bohand help",
			"hide": true,
            "info": "variable:bohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bcoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bopaper0",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper1",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper2",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper3",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper4",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper5",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper6",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper7",
            "translation": "Brown Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "boscissors0",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors1",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors2",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors3",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors4",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors5",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors6",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors7",
            "translation": "Brown Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "borock0",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock1",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock2",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock3",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock4",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock5",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock6",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock7",
            "translation": "Brown Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "bohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sohand0",
            "translation": "Silver Hand",
			"help": "variable:sohand help",
            "info": "variable:sohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand1",
            "translation": "Silver Hand [1]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand2",
            "translation": "Silver Hand [2]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand3",
            "translation": "Silver Hand [3]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand4",
            "translation": "Silver Hand [4]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand5",
            "translation": "Silver Hand [5]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand6",
            "translation": "Silver Hand [6]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand7",
            "translation": "Silver Hand [7]",
			"help": "variable:sohand help",
			"hide": true,
            "info": "variable:sohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sopaper0",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper1",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper2",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper3",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper4",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper5",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper6",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper7",
            "translation": "Silver Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "soscissors0",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors1",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors2",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors3",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors4",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors5",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors6",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors7",
            "translation": "Silver Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "sorock0",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock1",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock2",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock3",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock4",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock5",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock6",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock7",
            "translation": "Silver Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "sohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gohand0",
            "translation": "Gold Hand",
			"help": "variable:gohand help",
            "info": "variable:gohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand1",
            "translation": "Gold Hand [1]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand2",
            "translation": "Gold Hand [2]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand3",
            "translation": "Gold Hand [3]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand4",
            "translation": "Gold Hand [4]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand5",
            "translation": "Gold Hand [5]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand6",
            "translation": "Gold Hand [6]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand7",
            "translation": "Gold Hand [7]",
			"help": "variable:gohand help",
			"hide": true,
            "info": "variable:gohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team gsoddball" },
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gopaper0",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper1",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper2",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper3",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper4",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper5",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper6",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper7",
            "translation": "Gold Paper",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "goscissors0",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors1",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors2",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors3",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors4",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors5",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors6",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors7",
            "translation": "Gold Scissors",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gorock0",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock1",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock2",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock3",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock4",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock5",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock6",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock7",
            "translation": "Gold Rock",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "gohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "vvhand0",
            "translation": "Voodoo Hand",
			"help": "variable:vvhand help",
            "info": "variable:vvhand info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun0","cancel": [ "shield" ]
                    },
                    "shield": {"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield0","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand0x",
            "translation": "Voodoo Hand",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun0","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield0","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand1",
            "translation": "Voodoo Hand [1]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun1","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield1","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand1x",
            "translation": "Voodoo Hand [1]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun1","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield1","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand2",
            "translation": "Voodoo Hand [2]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun2","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield2","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand2x",
            "translation": "Voodoo Hand [2]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun2","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield2","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand3",
            "translation": "Voodoo Hand [3]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun3","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield3","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand3x",
            "translation": "Voodoo Hand [3]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun3","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield3","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand4",
            "translation": "Voodoo Hand [4]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun4","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield4","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand4x",
            "translation": "Voodoo Hand [4]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun4","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield4","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand5",
            "translation": "Voodoo Hand [5]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun5","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield5","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand5x",
            "translation": "Voodoo Hand [5]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun5","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield5","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand6",
            "translation": "Voodoo Hand [6]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun6","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield6","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand6x",
            "translation": "Voodoo Hand [6]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": {
				"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun6","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield6","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand7",
            "translation": "Voodoo Hand [7]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": {
						"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun7","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": 0,"common": "Self","silent": true, "silentConvert": true,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield7","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand7x",
            "translation": "Voodoo Hand [7]",
			"help": "variable:vvhand help",
			"hide": true,
            "info": "variable:vvhand info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": {
						"startup": "team-reveal-with-roles",
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {"command": [ "copy" ], "hide": true, "priority": 0,"common": "Self","silent": true, "silentCopy": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun7","cancel": [ "shield" ]
                    },
                    "shield": {"command": [ "convert" ], "hide": true, "priority": 0,"common": "Self","silent": true, "silentConvert": true, "charges": 2, "recharge": 2, "limit": 1,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield7","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvshield0",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield1",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield2",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield3",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield4",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield5",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield6",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield7",
            "translation": "Voodoo Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvgun0",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand0",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun1",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand1",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun2",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand2",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun3",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand3",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun4",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand4",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun5",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand5",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun6",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand6",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun7",
            "translation": "Voodoo Gun",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": {
                        "cursedRole": "vvhand7",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "hand",
            "translation": "Coloured Hand",
			"hide": true,
			"help": "variable:vvhand help",
            "info": "variable:vvhand info",
            "side": "voodoo",
            "actions": {
                "night": {
                    "Rock, Paper or Scissor": {"command": [ "dummy" ], "priority": 2,"common": "Self", "broadcast": "team","target": "AnyButTeam"
                    }
                }
            }
        }
    ],
    "roles1": [
        "rwhand3",
        "bchand3",
        "cohand3"
    ],
    "roles2": [
        "bchand3",
        "mchand3",
        "rwhand3",
		"ywhand3"
    ],
    "roles3": [
        "rwhand3",
		"swhand3",
        "bchand3",
        "gchand3",
		"vvhand3x"
    ],
    "roles4": [
        "rwhand5",
		"swhand5",
        "bchand5",
        "gchand5",
		"cohand5",
		"bohand5",
		"vvhand5x"
    ],
    "roles5": [
        "rwhand5",
        "bchand5",
		"owhand5",
		"ywhand5",
        "gchand5",
		"swhand5",
		"pchand5",
		"mchand5"
    ],
    "roles6": [
        "rwhand5",
		"swhand5",
		"owhand5",
        "bchand5",
        "gchand5",
		"pchand5",
		"cohand5",
		"bohand5",
		"gohand5"
    ],
    "roles7": [
        "rwhand7",
		"swhand7",
		"owhand7",
        "bchand7",
        "gchand7",
		"pchand7",
		"cohand7",
		"bohand7",
		"gohand7",
		"vvhand6x"
    ],
    "roles8": [
        "rwhand7",
		"swhand7",
		"owhand7",
        "bchand7",
        "gchand7",
		"pchand7",
		"cohand7",
		"bohand7",
		"gohand7",
		"vvhand4x",
		"vvhand4x"
    ],
    "roles9": [
        "rwhand7",
		"swhand7",
		"owhand7",
		"ywhand7",
        "bchand7",
        "gchand7",
		"pchand7",
		"mchand7",
		"cohand7",
		"bohand7",
		"gohand7",
		"sohand7",
		"vvhand7x"
    ],
    "changelog": {
        "February 2014": "Theme created."
    }
}
