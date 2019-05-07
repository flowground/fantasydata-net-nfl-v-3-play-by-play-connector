# ![LOGO](logo.png) NFL v3 Play-by-Play **flow**ground Connector

## Description

A generated **flow**ground connector for the NFL v3 Play-by-Play API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/nfl-v3-play-by-play/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:35+03:00

## API Description

NFL play-by-play API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Play By Play

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        
* `hometeam` - _required_ - Abbreviation of the home team. Example: <code>WAS</code>.

### Play By Play Delta

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        
* `minutes` - _required_ - Only returns player statistics that have changed in the last X minutes.  You specify how many minutes in time to go back.  Valid entries are:<br>
          <code>1</code> or <code>2</code>.
        

### Play By Play Simulation

> Gets simulated live play-by-play of NFL games, covering the Conference Championship games on January 21, 2018.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `numberofplays` - _required_ - The number of plays to progress in this NFL live game simulation. Example entries are <code>0</code>, <code>1</code>, <code>2</code>, <code>3</code>, <code>150</code>, <code>200</code>, etc.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-nfl-v-3-play-by-play-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
