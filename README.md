# livechart.me JSON raw data
A JSON raw data crawled from livechart.me used for supporting more data fields got from [anime-offline-database](https://github.com/manami-project/anime-offline-database) - [livechart.me](https://www.livechart.me/) metadata provider.
#### Last update: 25/08/2021 (9471 entries)

## Structure
This repository contains a JSON file which is an array of Anime and has the following model structure.

### livechart-raw-data.json

#### Data types:

**Anime**
| Field | Type | Nullable |
| --- | --- | --- |
| liveChartId | ```number``` | no |
| title | ```string``` | no |
| originalTitle | ```string``` | no |
| description | ```string``` | no |
| premiere | ```string``` | no |
| officialWebsiteURL | ```string``` | no |
| twitterURL | ```string``` | no |
| format | ```string``` | no |
| source | ```string``` | no |
| episodes | ```string``` | no |
| runTime | ```string``` | no |
| tags | ```string[]``` | yes |
| studio | ```string``` | no |
| externalResources | ```string[]``` | no |

#### Example:

```json
[
    {
        "liveChartId": 2,
        "title": "Watashi ga Motenai no wa Dou Kangaete mo Omaera ga Warui! WATAMOTE: No Matter How I Look at It, It\u2019s You Guys Fault I\u2019m Not Popular!",
        "originalTitle": "\u79C1\u304C\u30E2\u30C6\u306A\u3044\u306E\u306F\u3069\u3046\u8003\u3048\u3066\u3082\u304A\u524D\u3089\u304C\u60AA\u3044!",
        "description": "At the tender age of 15, Kuroki Tomoko has already dated dozens and dozens of boys and she\u0026#39;s easily the most popular girl around! The only problem is that absolutely none of that is real, and her perfect world exists only via dating games and romance shows. In fact, the sad truth is that she gets tongue tied just talking to people, and throughout middle school she\u0026#39;s only had one actual friend. All of which makes Kuroki\u0026#39;s entrance into the social pressure cooker of high school a new and special kind of hell. Because while Kuroki desperately wants to be popular, she\u0026#39;s actually worse off than she would be if she was completely clueless as to how to go about it. After all, the things that work in \u0026quot;otome\u0026quot; games rarely play out the same way in reality, especially when the self-appointed \u0026quot;leading lady\u0026quot; isn\u0026#39;t the paragon she thinks she is. There\u0026#39;s not much gain and plenty of pain ahead, but even if it happens again and again, there\u0026#39;s always someone else to blame in WATAMOTE ~ No Matter How I Look at It, It\u0026#39;s You Guys\u0026#39; Fault I\u0026#39;m Not Popular!",
        "premiere": "July 9, 2013",
        "officialWebsiteURL": "http://watamote.jp",
        "twitterURL": "https://twitter.com/watamote_PR",
        "format": "TV",
        "source": "Manga",
        "episodes": "12",
        "runTime": "24 min",
        "tags": [
            "Comedy",
            "School",
            "Shounen",
            "Slice of Life"
        ],
        "studio": "SILVER LINK.",
        "externalResources": [
            "https://anilist.co/anime/16742",
            "https://myanimelist.net/anime/16742",
            "http://anidb.net/a9582",
            "http://www.anime-planet.com/anime/watashi-ga-motenai-no-wa-dou-kangaetemo-omaera-ga-warui",
            "https://www.anisearch.com/anime/8287",
            "https://kitsu.io/anime/7504",
            "https://www.livechart.me/anime/2"
        ]
    }
]
