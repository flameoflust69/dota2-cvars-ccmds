# ChangeLog

## 2024-04-03, Version 6023 (Current)
### ConVar
* Update `r_legacy_vsync`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | devonly | devonly, hidden |
| flagsRaw | 2 | 18 |
| hasDefensiveFlag | false | true |

## 2024-03-21, Version 6017

<https://github.com/flameoflust69/dota2-cvars-ccmds/commit/7fed0f3>

### ConVar
* Add `dota_blog_image_accept_match`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client, hidden",
    "flagsRaw": 26,
    "hasDefensiveFlag": true
}
```
* Add `dota_show_accept_match_details`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "client, archive, per_user",
    "flagsRaw": 32904,
    "hasDefensiveFlag": false
}
```

### ConCommand
* Update `dota_fake_accept_match`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | devonly, client | devonly, client, hidden |
| flagsRaw | 10 | 26 |
| hasDefensiveFlag | false | true |

## 2024-03-11, Version 6011

<https://github.com/flameoflust69/dota2-cvars-ccmds/commit/1c30bde>

* Initial version
* Fix wrong ConCommand index