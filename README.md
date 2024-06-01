# Dota2 ConVar and ConCommand dump

```
Build version: 6082
Build info: May 31 2024 - 17:45:25PST
Total ConVar: 4622
Total ConCommand: 1532
```

ConVar/ConCommand dump only comes from `ICvar` there are some hidden commands, such as `dota_captain_ban_hero npc_dota_hero_%s` used for banning heroes or any other commands from workshop tools.

## Flags
> [!NOTE]  
> ConVar/ConCommand with `FCVAR_DEVELOPMENTONLY` and defensive flag `false` can't be used.

```c++
enum ConVarFlags_t : int {
	FCVAR_NONE = 0,
	FCVAR_LINKED_CONCOMMAND = (1 << 0),

	FCVAR_DEVELOPMENTONLY = (1 << 1),
	FCVAR_GAMEDLL = (1 << 2),
	FCVAR_CLIENTDLL = (1 << 3),	
	FCVAR_HIDDEN = (1 << 4),

	FCVAR_PROTECTED = (1 << 5),
	FCVAR_SPONLY = (1 << 6),
	FCVAR_ARCHIVE = (1 << 7),
	FCVAR_NOTIFY = (1 << 8),
	FCVAR_USERINFO = (1 << 9),

	FCVAR_UNLOGGED = (1 << 11),

	FCVAR_REPLICATED = (1 << 13),

	FCVAR_CHEAT = (1 << 14),

	FCVAR_PER_USER = (1 << 15),
	FCVAR_DEMO = (1 << 16),
	FCVAR_DONTRECORD = (1 << 17),
	FCVAR_RELEASE = (1 << 19),
	FCVAR_MENUBAR_ITEM = (1 << 20),

	FCVAR_NOT_CONNECTED = (1 << 22),

	FCVAR_VCONSOLE_FUZZY_MATCHING = (1 << 23),

	FCVAR_SERVER_CAN_EXECUTE = (1 << 24),
	FCVAR_SERVER_CANNOT_QUERY = (1 << 26),
	FCVAR_VCONSOLE_SET_FOCUS = (1 << 27),
	FCVAR_CLIENTCMD_CAN_EXECUTE = (1 << 28),

	FCVAR_EXECUTE_PER_TICK = (1 << 29),
};
```

## ConVar Type
```c++
enum ConVarType_t : short
{
	CONVAR_TYPE_INVALID = -1,    // Maybe unused
	CONVAR_TYPE_BOOL,
	CONVAR_TYPE_INT16,           // Maybe unused
	CONVAR_TYPE_UINT16,          // Maybe unused
	CONVAR_TYPE_INT32,
	CONVAR_TYPE_UINT32,
	CONVAR_TYPE_INT64,           // Maybe unused
	CONVAR_TYPE_UINT64,
	CONVAR_TYPE_FLOAT,
	CONVAR_TYPE_DOUBLE,          // Maybe unused
	CONVAR_TYPE_STRING,
	CONVAR_TYPE_COLOR,
	CONVAR_TYPE_VECTOR2,
	CONVAR_TYPE_VECTOR3,
	CONVAR_TYPE_VECTOR4,         // Maybe unused
	CONVAR_TYPE_QANGLE,          // Maybe unused
};
```

## Credits
- https://cs2.poggu.me/dumped-data/command-list/
- https://github.com/alliedmodders/hl2sdk/tree/cs2
- https://github.com/saul/cvar-unhide-s2