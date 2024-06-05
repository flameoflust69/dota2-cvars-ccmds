# ChangeLog

Select a version below to view the changelog history:

* [2024-06-04, Version 6084](#2024-06-04-version-6084-current) **Current**
* [2024-05-31, Version 6082](#2024-05-31-version-6082)
* [2024-05-28, Version 6077](#2024-05-28-version-6077)
* [2024-05-22, Version 6063](#2024-05-22-version-6063)
* [2024-05-07, Version 6053](#2024-05-07-version-6053)
* [2024-05-06, Version 6051](#2024-05-06-version-6051)
* [2024-04-18, Version 6027](#2024-04-18-version-6027)
* [2024-04-03, Version 6023](#2024-04-03-version-6023)
* [2024-03-21, Version 6017](#2024-03-21-version-6017)
* [2024-03-11, Version 6011](#2024-03-11-version-6011)

***

***

## 2024-06-04, Version 6084 (Current)

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/668fcdc>

### ConVar
* Update `dota_crownfall_fishing_spear_hit_radius`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | 100 | 110 |

## 2024-05-31, Version 6082

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/6081fa1>

### ConCommand
* Add `dota_ability_draft_dump_heroes`
```json
{
    "description": "wtf",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": true
}
```

## 2024-05-28, Version 6077

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/6081fa1>

### ConVar
* Add `dota_crownfall_fishing_cheat_big_fish_only`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```

## 2024-05-22, Version 6063

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/83828b4>  
> Blog: https://www.dota2.com/newsentry/5991554339562872856

### ConVar
* Add `always_animate_clientside_worldgroups`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "Experimental fix for world panel animation issues",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `animgraph_slope_drop_use_capsule`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": true
}
```
* Add `animgraph_slope_drop_use_capsule_smoothing`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": true
}
```
* Add `animgraph_slope_drop_use_capsule_soft_cliffs`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": true
}
```
* Add `cl_skip_hierarchy_update_for_unchanged_entities`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "Skip updating hierarchy information in PostDataUpdate for entities that have not changed",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `cloth_filter_transform_stateless`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "Enable the new, stateless version of FilterTransform",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `dota_alt_right_range_hint`
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
* Add `dota_crownfall_fishing_score_multiplier`
```json
{
    "data_type": "float",
    "default_value": "1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_spear_hit_radius`
```json
{
    "data_type": "float",
    "default_value": "100",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_spear_throw_time`
```json
{
    "data_type": "float",
    "default_value": "0.7",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_flappy_debug_draw`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_flappy_debug_fast_movement`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_flappy_debug_no_death`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_intro_state_act_2`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 136,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_intro_state_act_3`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 136,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_intro_state_act_4`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 136,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_map_disable_camera_events`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client, archive",
    "flagsRaw": 138,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_most_recent_active_season_id`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 136,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_pit_fighter_disable_checks`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_reset_map_also_resets_event`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, client, archive",
    "flagsRaw": 138,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_suppress_popups_when_completing_nodes`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client, archive",
    "flagsRaw": 138,
    "hasDefensiveFlag": false
}
```
* Add `dota_enigma_gravity_max`
```json
{
    "data_type": "float",
    "default_value": "90",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `dota_enigma_gravity_min`
```json
{
    "data_type": "float",
    "default_value": "60",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `dota_enigma_gravity_scale_divisor`
```json
{
    "data_type": "float",
    "default_value": "1",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `dota_health_bar_hovered_always_top`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_hero_demo_default_enemy_variant`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 1073741960,
    "hasDefensiveFlag": false
}
```
* Add `dota_hero_force_respawn_time`
```json
{
    "data_type": "float",
    "default_value": "-1",
    "description": "",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": false
}
```
* Add `dota_show_chronocube_debug`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": false
}
```
* Add `dota_show_facet_help`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 136,
    "hasDefensiveFlag": false
}
```
* Add `engine_frametime_amnesty_debug`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "Enable logging about events that disable frame time warnings",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `hairsim_force_fixed_timestep`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `lb_csm_override_bulb_radius`
```json
{
    "data_type": "float",
    "default_value": "-1",
    "description": "Override bulb radius for CSM",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `lb_debug_shadowtile_atlas`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "SceneSystem/LightBinner/Debug ShadowTile Atlas",
    "flags": "devonly, cheat, menubar_item",
    "flagsRaw": 1064962,
    "hasDefensiveFlag": false
}
```
* Add `phys_threaded_kinematic_bone_update`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": true
}
```
* Add `r_physics_particle_op_spawn_scale`
```json
{
    "data_type": "float",
    "default_value": "1",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```
* Add `ragdoll_move_entity`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "game, client, replicated, cheat",
    "flagsRaw": 24588,
    "hasDefensiveFlag": false
}
```
* Add `ragdoll_update_from_weights`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "game, client, replicated, cheat",
    "flagsRaw": 24588,
    "hasDefensiveFlag": false
}
```
* Add `rtx_dynamic_blas`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "Allow dynamic BLAS creation for geometry going through the compute shader skinning path.",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `snd_group_priority_debug`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "replicated, cheat",
    "flagsRaw": 24576,
    "hasDefensiveFlag": false
}
```
* Add `snd_group_priority_max_tolerance`
```json
{
    "data_type": "float",
    "default_value": "0.05",
    "description": "",
    "flags": "replicated, cheat",
    "flagsRaw": 24576,
    "hasDefensiveFlag": false
}
```
* Add `sv_early_network_message_processing`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "Processes network messages on the server before entities think, instead of at the end of the tick.",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": false
}
```
* Add `sv_vac_webapi_auth_key`
```json
{
    "data_type": "string",
    "default_value": "",
    "description": "Key for when posting to vac related webapis.",
    "flags": "game, release",
    "flagsRaw": 524292,
    "hasDefensiveFlag": false
}
```

* Update `lb_debug_shadow_atlas`, `mat_show_distance_field`, `sv_long_frame_ms` description

* Rename `engine_enable_frametime_warnings` to `engine_frametime_warnings_enable`

* Update `cl_parallel_readpacketentities_threshold`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | 8 | 2 |

* Update `dota_local_map_strategy_time`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | false | true |

* Remove
  * `cl_clock_recvmargin_enable`
  * `cl_parallel_readpacketentities_type`
  * `cl_profilereadpacketentities`
  * `cl_tickpacket_recvmargin_enable`
  * `cq_force_percent`
  * `dota_fake_event_wins`
  * `dota_fake_event_wins_claimed`
  * `dota_profile_card_no_compendium`
  * `dota_profile_card_no_event`
  * `dota_puck_waning_rift_doubletap_distance`
  * `nav_search_lattice_initial_scale`
  * `nav_search_lattice_progressive_scale`
  * `pregame_debug_base_event_points`
  * `pregame_debug_event_points`
  * `r_fallback_texture_orange`
  * `volume_fog_disable`

### ConCommand
* Add `cl_dump_response_symbols`
```json
{
    "description": "print all response symbols to the console",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_crownfall_encounter_flappy_skywrath`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_overworld_map_test_comet`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dump_response_symbols`
```json
{
    "description": "print all response symbols to the console",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": true
}
```
* Add `engine_frametime_print_report`
```json
{
    "description": "Print a performance report from the current data in the vprof 'lite' profiler",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `rangefinder2d`
```json
{
    "description": "Measures distance along a ray, only measuring along XY plane.",
    "flags": "game, cheat",
    "flagsRaw": 16388,
    "hasDefensiveFlag": false
}
```
* Add `test_voice_container_nesting`
```json
{
    "description": "Test nesting voice containers.",
    "flags": "linked, devonly",
    "flagsRaw": 3,
    "hasDefensiveFlag": true
}
```
* Add `voice_containers_get_instance_args`
```json
{
    "description": "Args: [Voice Container Path]",
    "flags": "linked, devonly",
    "flagsRaw": 3,
    "hasDefensiveFlag": true
}
```

* Update `dota_overworld_trade_tokens` description

* Remove
  * `generate_voice_containers`
  * `rpestats`

## 2024-05-07, Version 6053

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/52e0cac>

### ConVar
* Add `temp_dota_legacy_keys_in_use`
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

## 2024-05-06, Version 6051

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/8db15e6>  
> Blog: https://www.dota2.com/newsentry/4177727597572918930

### ConVar
* Add `dota_crownfall_collectors_cache_vote_shuffle_enabled`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_experimental_target_filter_is_toggle`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "client, archive, per_user",
    "flagsRaw": 32904,
    "hasDefensiveFlag": false
}
```
* Add `dota_hud_healthbar_local_player_high_visibility`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "client, archive, per_user",
    "flagsRaw": 32904,
    "hasDefensiveFlag": false
}
```

* Update `dota_hud_healthbar_experimental_local_color_white`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | client, archive, per_user | devonly, client |
| flagsRaw | 32904 | 10 |
| hasDefensiveFlag | false | true |

### ConCommand
* Add `+dota_filter_ally`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `+dota_filter_enemy`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `+dota_filter_hero`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `+dota_filter_non_hero`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `-dota_filter_ally`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `-dota_filter_enemy`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `-dota_filter_hero`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `-dota_filter_non_hero`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_show_crownfall_collectors_cache_vote_page`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```

## 2024-04-18, Version 6027

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/f66bf06>  
> Blog: https://www.dota2.com/newsentry/4178852863469164127

### ConVar
* Add `attached_output_stall_ms`
```json
{
    "data_type": "float",
    "default_value": "250",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `cl_debug_force_push_to_talk`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `demo_playback_override_settings`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_cache_duration_charge_cost_item_purchase_s`
```json
{
    "data_type": "int32",
    "default_value": "1800",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_crownfall_fishing_aim_fov`
```json
{
    "data_type": "float",
    "default_value": "50",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_bar_max_size`
```json
{
    "data_type": "float",
    "default_value": "100",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_bite_max_delay`
```json
{
    "data_type": "float",
    "default_value": "6.5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_bite_min_delay`
```json
{
    "data_type": "float",
    "default_value": "2.5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_cast_rod_anim_time`
```json
{
    "data_type": "float",
    "default_value": "0.5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_catch_bar_increase_per_miss`
```json
{
    "data_type": "float",
    "default_value": "3",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_catch_bar_size`
```json
{
    "data_type": "float",
    "default_value": "24",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_catch_energy_fish_escape`
```json
{
    "data_type": "float",
    "default_value": "1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_catch_energy_grace_time`
```json
{
    "data_type": "float",
    "default_value": "0.25",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_catch_energy_initial`
```json
{
    "data_type": "float",
    "default_value": "2",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_catch_energy_needed`
```json
{
    "data_type": "float",
    "default_value": "5.5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_caught_fish_anim_time`
```json
{
    "data_type": "float",
    "default_value": "1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_fish_escape_max_time`
```json
{
    "data_type": "float",
    "default_value": "1.5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_fish_escape_min_time`
```json
{
    "data_type": "float",
    "default_value": "0.7",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_fish_tire_time`
```json
{
    "data_type": "float",
    "default_value": "7",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_max_cast_distance`
```json
{
    "data_type": "float",
    "default_value": "1050",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_max_cast_strength`
```json
{
    "data_type": "float",
    "default_value": "80",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_min_cast_distance`
```json
{
    "data_type": "float",
    "default_value": "400",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_num_lures`
```json
{
    "data_type": "int32",
    "default_value": "5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_post_catch_anim_time`
```json
{
    "data_type": "float",
    "default_value": "1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_fishing_show_tips_point_threshold`
```json
{
    "data_type": "int32",
    "default_value": "1000",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_intro_state`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive",
    "flagsRaw": 136,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_map_fow`
```json
{
    "data_type": "int32",
    "default_value": "1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_node_tooltip_show_delay`
```json
{
    "data_type": "float",
    "default_value": "0.2",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_crownfall_sticky_tooltip_time_required`
```json
{
    "data_type": "float",
    "default_value": "0.4",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_crownfall_store_fake_coins`
```json
{
    "data_type": "int32",
    "default_value": "-1",
    "description": "Fake the number of coins shown in the UI. -1 disables it.",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_visual_novel_max_portraits_in_group`
```json
{
    "data_type": "int32",
    "default_value": "3",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_visual_novel_text_audio_interval`
```json
{
    "data_type": "float",
    "default_value": "0.06",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_notify_steam_when_client_update_required`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "When we detect the client is out of date, notify SteamAPI  to request an update",
    "flags": "client, release",
    "flagsRaw": 524296,
    "hasDefensiveFlag": false
}
```
* Add `dota_overlaymap_inputmode`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive, per_user",
    "flagsRaw": 32904,
    "hasDefensiveFlag": false
}
```
* Add `dota_overlaymap_togglemode`
```json
{
    "data_type": "int32",
    "default_value": "0",
    "description": "",
    "flags": "client, archive, per_user",
    "flagsRaw": 32904,
    "hasDefensiveFlag": false
}
```
* Add `dota_overworld_test_pre_game`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_suggest_ranks_force_enable`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": true
}
```
* Add `func_mover_enable_debug_visualization`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": true
}
```
* Add `hairsim_reset`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `imgui_default_font_size`
```json
{
    "data_type": "float",
    "default_value": "20",
    "description": "Default imgui font size",
    "flags": "archive, cheat",
    "flagsRaw": 16512,
    "hasDefensiveFlag": false
}
```
* Add `lb_allow_shadow_rotation`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "SceneSystem/LightBinner/Shadow Rotation",
    "flags": "devonly, cheat, menubar_item",
    "flagsRaw": 1064962,
    "hasDefensiveFlag": false
}
```
* Add `nav_find_occluded_node_nozup_use_raycast`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "game, cheat",
    "flagsRaw": 16388,
    "hasDefensiveFlag": false
}
```
* Add `nav_smooth_spring_enable`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "game, cheat",
    "flagsRaw": 16388,
    "hasDefensiveFlag": false
}
```
* Add `particle_cluster_use_collision_hulls`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": true
}
```
* Add `path_simple_closest_point_on_path_debug`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_pos_max`
```json
{
    "data_type": "float",
    "default_value": "2",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_pos_multiplier`
```json
{
    "data_type": "float",
    "default_value": "0.5",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_pos_strength`
```json
{
    "data_type": "float",
    "default_value": "0.25",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_rot_high`
```json
{
    "data_type": "float",
    "default_value": "0.1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_rot_low`
```json
{
    "data_type": "float",
    "default_value": "0.01",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_rot_multiplier`
```json
{
    "data_type": "float",
    "default_value": "0.3",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pred_cloth_substeps`
```json
{
    "data_type": "int32",
    "default_value": "1",
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `pulse_save_execution_history`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "Keep a history of all instructions run on a per graph basis.",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `pulse_save_execution_history_limit`
```json
{
    "data_type": "int32",
    "default_value": "10000",
    "description": "Keep a history of all instructions run on a per graph basis.",
    "flags": "devonly, game, client, replicated",
    "flagsRaw": 8206,
    "hasDefensiveFlag": false
}
```
* Add `r_force_thick_hair`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `reset_voice_on_input_stallout`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "If true, resets the input device when there was a long enough hitch between callbacks.",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```
* Add `sc_instanced_mesh_lod_bias`
```json
{
    "data_type": "float",
    "default_value": "1.25",
    "description": "Bias for LOD selection of instanced meshes",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `sc_instanced_mesh_lod_bias_shadow`
```json
{
    "data_type": "float",
    "default_value": "1.75",
    "description": "Bias for LOD selection of instanced meshes in shadowmaps",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `sc_instanced_mesh_size_cull_bias`
```json
{
    "data_type": "float",
    "default_value": "1.5",
    "description": "Bias for size culling of instanced meshes",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `sc_instanced_mesh_size_cull_bias_shadow`
```json
{
    "data_type": "float",
    "default_value": "2",
    "description": "Bias for size culling instanced meshes in shadowmaps",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `steamlearn_override_inference_versions`
```json
{
    "data_type": "string",
    "default_value": "",
    "description": "Versions for overriding inference keys",
    "flags": "devonly, game",
    "flagsRaw": 6,
    "hasDefensiveFlag": false
}
```
* Add `sv_steamauth_enforce`
```json
{
    "data_type": "int32",
    "default_value": "2",
    "description": "By default, player must maintain a reliable connection to Steam servers. When player Steam session drops, enforce it: 2 = instantly kick, 1 = kick at next spawn, 0 = do not kick.",
    "flags": "release",
    "flagsRaw": 524288,
    "hasDefensiveFlag": false
}
```
* Add `tv_secure_bypass`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "Bypass secure challenge on TV port",
    "flags": "release",
    "flagsRaw": 524288,
    "hasDefensiveFlag": false
}
```
* Add `v8_jitless`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "Disable runtime allocation of executable memory for V8.",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```
* Add `v8_maximum_heap_size_mb`
```json
{
    "data_type": "int32",
    "default_value": "512",
    "description": "Hard limit for the v8 heap size (in mBytes)",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```
* Add `v8_stack_size`
```json
{
    "data_type": "int32",
    "default_value": "384",
    "description": "Default size of stack region v8 is allowed to use (in kBytes)",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```
* Add `volume_fog_debug_volumes`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "",
    "flags": "cheat",
    "flagsRaw": 16384,
    "hasDefensiveFlag": false
}
```
* Add `volume_fog_depth_warp`
```json
{
    "data_type": "float",
    "default_value": "7",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `volume_fog_force_indirect_lpvs`
```json
{
    "data_type": "bool",
    "default_value": "false",
    "description": "Force use of LPVs for indirect lighting in fog",
    "flags": "devonly, cheat",
    "flagsRaw": 16386,
    "hasDefensiveFlag": false
}
```
* Add `volume_fog_shadow_penumbra_multiplier`
```json
{
    "data_type": "float",
    "default_value": "3",
    "description": "Penumbra size multiplier for shadow sampling, reduces fog shadow aliasing",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `volume_fog_temporal_filter`
```json
{
    "data_type": "bool",
    "default_value": "true",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `volume_fog_temporal_weight`
```json
{
    "data_type": "float",
    "default_value": "0.9",
    "description": "Temporal filtering weight",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `xxx`
```json
{
    "data_type": "int32",
    "default_value": "1",
    "description": "",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```

* Update `r_low_latency`, `r_size_cull_threshold_shadow` description

* Update `cl_ticks_warning_level`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | 1 | 0 |

* Update `cq_min_queue_size`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | game, release | game, client, replicated, release |
| flagsRaw | 524292 | 532492 |

* Update `nav_smooth_spring_const_override`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | 0 | -1 |

* Update `r_smooth_morph_normals`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | devonly | release |
| flagsRaw | 2 | 524288 |
| hasDefensiveFlag | true | false |

* Update `sv_enable_donttransmit`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | false | true |

* Update `voice_input_stallout`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | 0.2 | 2 |
| flags | client, archive | devonly |
| flagsRaw | 136 | 2 |

* Update `volume_fog_dither_scale`

| Field | Old | New |
| :--- | :--- | :--- |
| default_value | 3 | 1 |

* Remove
  * `cloth_smooth_mouse`
  * `dota_overlaymap_acceptsinput`
  * `nav_draw_markup_offset`
  * `nav_smooth_calc_z`
  * `nav_smooth_separating_dist_override`
  * `nav_split_place_on_ground`
  * `pa_arcana_level`
  * `particle_use_gpu_particle_model_collection`
  * `phys_client_clear_shadow_velocity`
  * `phys_controller_clear_velocity`
  * `phys_server_clear_shadow_velocity`
  * `r_drawsprites`
  * `r_particle_newcode`
  * `volume_fog_clipmap_update`
  * `volume_fog_clipmaps_enabled`
  * `volume_fog_enable_stereo`
  * `volume_fog_enlarge_frusta`
  * `volume_fog_jitter_offset_random`
  * `volume_fog_show_volumes`

### ConCommand
* Add `+dota_hud_overlaymap_inputkey`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `-dota_hud_overlaymap_inputkey`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_crownfall_candy_shop_show_page`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_encounter_fishing`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_encounter_token_treasure`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_overworld_map_test_drag_zoom`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_reset_intro`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_show_tokens_received`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_crownfall_visual_novel_dialogue`
```json
{
    "description": "",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_fake_charge_cost_item_charges_in_flight`
```json
{
    "description": "<itemdef> <quantity> - overrides the UI to display as if you have the given value of charges for an item def in flight. Set to -1 to disable.",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": false
}
```
* Add `dota_overworld_trade_tokens`
```json
{
    "description": "Usage: dota_overworld_trade_tokens <token_id request> <token_id offer1> <token_id offer2> <token_id offer3>[ token_id offer4 ]",
    "flags": "devonly, client",
    "flagsRaw": 10,
    "hasDefensiveFlag": true
}
```
* Add `dota_test_hero_token_popup`
```json
{
    "description": "Show the hero token popup.",
    "flags": "devonly, client, cheat",
    "flagsRaw": 16394,
    "hasDefensiveFlag": false
}
```
* Add `generate_null_container`
```json
{
    "description": "Generated a nulled out container.",
    "flags": "linked, devonly",
    "flagsRaw": 3,
    "hasDefensiveFlag": true
}
```
* Add `imgui_cycle_undocked_window_focus`
```json
{
    "description": "Cycles focus between the game window and undocked imgui windows",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": true
}
```
* Add `print_changed_convars`
```json
{
    "description": "Prints all convars that have changed from their default value",
    "flags": "release",
    "flagsRaw": 524288,
    "hasDefensiveFlag": false
}
```
* Add `pulse_print_graph_execution_history`
```json
{
    "description": "Prints the execution history of a graph by filename or instanceid",
    "flags": "cheat",
    "flagsRaw": 16384,
    "hasDefensiveFlag": false
}
```
* Add `r_renderdoc_capture_window_dx11`
```json
{
    "description": "Triggers a RenderDoc capture of a specific Window",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```
* Add `spec_goto`
```json
{
    "description": "Move the spectator camera to a specific location. `spec_goto x y z pitch yaw`",
    "flags": "client, clientcmd_can_execute",
    "flagsRaw": 268435464,
    "hasDefensiveFlag": false
}
```
* Add `spec_player`
```json
{
    "description": "Spectate a player by name or slot",
    "flags": "client, clientcmd_can_execute",
    "flagsRaw": 268435464,
    "hasDefensiveFlag": false
}
```
* Add `v8_write_heap_stats`
```json
{
    "description": "Dump output of v8::Isolate::GetHeapStatistics.",
    "flags": "devonly",
    "flagsRaw": 2,
    "hasDefensiveFlag": false
}
```

* Update `cl_interp` description

* Update `snd_compare_soundevents`, `snd_list_deferred_soundevents`, `snd_list_soundevents`, `snd_list_soundevents_by_stack`, `snd_remove_all_soundevents`, `snd_remove_soundevent`, and `snd_soundevent_clear_deferred`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | cheat | devonly, cheat |
| flagsRaw | 16384 | 16386 |
| hasDefensiveFlag | false | false |

* Remove
  * `dota_map_locations_debug`
  * `time_asserts`
  * `voice_containers_generate_curve`
  * `world_map_reset`
  * `world_map_set_location_complete`

## 2024-04-03, Version 6023

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/e2968f3>

### ConVar
* Update `r_legacy_vsync`

| Field | Old | New |
| :--- | :--- | :--- |
| flags | devonly | devonly, hidden |
| flagsRaw | 2 | 18 |
| hasDefensiveFlag | false | true |

## 2024-03-21, Version 6017

> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/7fed0f3>  
> Blog: https://www.dota2.com/newsentry/6127782523022178336

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


> [!NOTE]
> Commit: <https://github.com/flameoflust69/dota2-cvars-ccmds/commit/1c30bde>

* Initial version
* Fix wrong ConCommand index