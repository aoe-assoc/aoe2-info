# Ideas

## Goal

The website should aggregate information on:
- Tournaments ([Liquipedia][liquipedia])
  - General AoE2-Events ([Liquipedia][liquipedia])
  - Clan Wars {Upcoming, Past} ([Liquipedia][liquipedia])
  - Matches {Upcoming, Past} ([Liquipedia][liquipedia])
  - Clans ([Liquipedia][liquipedia])
  - Player Profiles ([aoe2net][aoe2net] / [aoe2recs][aoe2recs] / [Liquipedia][liquipedia] / [Player data][playerdata])
  - Tournament-ELO (https://aoe-elo.com / [Liquipedia][liquipedia])

- News Blog
- Strategies/Guides (could go hand-in-hand with the blog)
  - Blogs are easily outdated, sometimes maintenance-Overkill
  - rethink if needed (could change basic design - with/withou cms)
  - Previews (https://aoecompanion.com/)
- Videos/Clips ([Twitch API][twitch-api])
- Active Livestreams ([Twitch API][twitch-api])
- Replays ([aoe2recs][aoe2recs])
- Stats ([aoe2recs][aoe2recs] / https://aoestats.io/)
- Maps (https://aoe2map.net/)
- Users ([aoe2net][aoe2net])
- Commonly used tools (BO tools, replay analyzers, overlays etc.)


From the user story side it should be possible to stay on this site and to be informed about mostly anything that is going on in the aoe2 universe. 
From tournament information and player info (pulled in from liquipedia), over active streams and most liked twitch clips from the last week (e.g.) (pulled in directly from twitch), with maybe even a small content management system for news articles.

This platform should be explicitly **not another discussion platform** but solely existing to give information and serve as an entrance into the esports community.
While collecting information and give an overview over places to inform oneself.


## Needed Components


# API docs
- [Liquipedia][liquipedia]
- [Twitch API][twitch-api]
- [aoe2net](https://aoe2.net/#api)
- [aoe2recs](https://aoe2recs.com/api)

[liquipedia]: https://liquipedia.net/ageofempires/api.php?action=help&modules=askargs
[twitch-api]: https://dev.twitch.tv/docs/v5
[aoe2recs]: https://aoe2recs.com
[aoe2net]: https://aoe2.net
[playerdata]: https://github.com/SiegeEngineers/aoc-reference-data/blob/master/data/players.yaml
