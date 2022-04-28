# Cyber Adversary Heatmaps
Intelligence around common attacker behaviors (MITRE ATT&amp;CK TTPs), in the form of ATT&amp;CK Navigator "layer" json files.

Paste .json file contents into the "Threat Intelligence" dropdown on the [Threat Alignment](https://controlcompass.github.io/risk) page of the open-source [Control Validation Compass](https://controlcompass.github.io/) project, to instantly surface technical & policy controls and offensive security tests for these techniques.

The following heatmap sets are currently available:

* April 2022: [CISA Alert AA22-110A]()
* March 2022: [Russia TTP Mappings](https://github.com/tropChaud/Russia-TTP-Mappings)

Unless otherwise noted, heatmaps will use the following base ATT&CK Navigator settings:

<code>
	{
	"name": "base",
	"versions": {
		"attack": "11",
		"navigator": "4.6.1",
		"layer": "4.3"
	},
	"domain": "enterprise-attack",
	"description": "",
	"filters": {
		"platforms": [
			"Linux",
			"macOS",
			"Windows",
			"PRE",
			"Containers",
			"Network",
			"Office 365",
			"SaaS",
			"Google Workspace",
			"IaaS",
			"Azure AD"
		]
	},
	"sorting": 0,
	"layout": {
		"layout": "side",
		"aggregateFunction": "max",
		"showID": false,
		"showName": true,
		"showAggregateScores": true,
		"countUnscored": false
	},
	"hideDisabled": false,
	"techniques": [],
	"gradient": {
		"colors": [
			"#ffffff",
			"#ff6666"
		],
		"minValue": 0,
		"maxValue": 1
	},
	"legendItems": [],
	"metadata": [],
	"links": [],
	"showTacticRowBackground": false,
	"tacticRowBackground": "#dddddd",
	"selectTechniquesAcrossTactics": true,
	"selectSubtechniquesWithParent": false
	}
</code>

MITRE ATT&CK® is a registered trademark of The MITRE Corporation
