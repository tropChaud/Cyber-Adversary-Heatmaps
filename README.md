# Cyber Adversary Heatmaps
Intelligence around common attacker behaviors (MITRE ATT&amp;CK TTPs), in the form of ATT&amp;CK Navigator "layer" json files.

Paste .json file contents into the "Threat Intelligence" dropdown on the **[Threat Alignment page](https://controlcompass.github.io/risk)** of the open-source [Control Validation Compass](https://controlcompass.github.io/) project, to instantly surface technical & policy controls and offensive security tests aligned with these techniques.

The following heatmap sets are currently available:

* April 2022: [CISA Alert AA22-110A](https://github.com/tropChaud/Cyber-Adversary-Heatmaps/tree/main/CISA%20Alert%20AA22-110A)
* March 2022: [Russia TTP Mappings](https://github.com/tropChaud/Cyber-Adversary-Heatmaps/tree/main/Russia-TTP-Mappings)

Want to learn more about using ATT&CK Navigator to visualize TTP intelligence? See the MITRE ATT&CK CTI Training [here](https://attack.mitre.org/resources/training/cti/), and ATT&CK Navigator documentation [here](https://github.com/mitre-attack/attack-navigator/blob/master/USAGE.md).

Unless otherwise noted, heatmaps will use the following base ATT&CK Navigator settings:

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

MITRE ATT&CK® is a registered trademark of The MITRE Corporation
